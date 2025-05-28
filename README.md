# Lab8-Starter
- Charlie Zhu
  
## How are graceful degradation and service workers related? 
- The two topics are related because graceful degradation is the principle that web applications should continue to function with reduced capabilities when running into issues, such as loss of internet conntection. Service workers directly help aid in this process by ensuring that websites continue to function well in spite of things such as loss of internet connection. They do so by caching our requests so that when we make a duplicate request (even if our internet is down), the website will continue to function.