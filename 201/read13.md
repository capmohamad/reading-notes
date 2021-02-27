about  storage mechanisms
There are several other storage mechanisms available in the browser,
 but they have limited use and may cause significant performance issues.

SessionStorage is tab specific, and scoped to the lifetime of the tab.
 It may be useful for storing small amounts of session specific information,
 for example an IndexedDB key. It should be used with caution because it is synchronous and will block the main thread. 
It is limited to about 5MB and can contain only strings. Because it is tab specific, it is not accessible from web workers or service workers.

LocalStorage should be avoided because it is synchronous and will block the main thread.
 It is limited to about 5MB and can contain only strings. LocalStorage is not accessible from web workers or service workers

 store space 
In short, a lot, at least a couple of hundred megabytes, and potentially hundreds of gigabytes or more.
 Browser implementations vary, but the amount of storage available is usually based on the amount of storage available on the device.