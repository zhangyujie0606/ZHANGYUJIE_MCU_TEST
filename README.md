ddff
# websocket - Tiny, cross platform websocket client C library.

### Features

- No additional dependecies
- Single header library interface librws.h with public methods
- Thread safe
- Send/receive logic in background thread

# websocket - Tiny, cross platform websocket client C library.

### Features

- No additional dependecies
- Single header library interface librws.h with public methods
- Thread safe
- Send/receive logic in background thread

### Example
##### Create and store websocket object handle
```c
  // Define variable or field for
# websocket - Tiny, cross platform websocket client C library.

### Features

- No additional dependecies
- Single header library interface librws.h with public methods
- Thread safe
- Send/receive logic in background thread

### Example
##### Create and store websocket object handle
```c
  // Define variable or field for socket handle
  rws_socket _socket = NULL;
  ............
  // Create socket object
  _socket = rws_socket_create();
```
##### Set websocket connection url
```c
// Combined url: "ws://echo.websocket.org:80/"
rws_socket_set_scheme(_socket, "ws");
rws_socket_set_host(_socket, "echo.websocket.org");
rws_socket_set_port(_socket, 80);
rws_socket_set_path(_socket, "/");
```
##### Set websocket responce callbacks
Warning: ```rws_socket_set_on_disconnected``` is required
```c
// Main callbacks functions
// callback trigered on socket di
# websocket - Tiny, cross platform websocket client C library.

### Features

- No additional dependecies
- Single header library interface librws.h with public methods
- Thread safe
- Send/receive logic in background thread
