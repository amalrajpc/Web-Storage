# Web-Storage

it is the technique that allow applications to store data in the client side so you can access it or manipulate it later.

### Session Storage

Session Storage allows data to be stored in the browser that will be cleared when the session ends or tab closes. The data stored in the session storage is independent of the tab or window.

### Local Storage

The data stored in the local storage persist even after the browser is closed. We have to delete the data manually. Local storage data get shared across the windows and tabs.

### Cookie

Cookies are small piece of data stored in the  browser and sent back to the server with each HTTP request. Data persist as per the expiry TTL set.

SessionStorage is more secure than LocalStorage because it can only be used within a browser tab. XSS attacks can affect both SessionStorage and LocalStorage. Thus, do not save sensitive information in the browser's store.

Improper user data verification at server side and storage of senstive data in web storage some times result in insecure direct object reference vulnerability (IDOR).  

Setting the secure flag true, allows cookie to be transmitted over an encrypted connection. The secure flag is used to protect against MITM attack.
This attribute protect against the confidentiality not the integrity.
The HTTP Only attribute against the XSS attack.



