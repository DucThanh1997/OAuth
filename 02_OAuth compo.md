# OAuth compo
## OAuth provider
Có 3 thành phần chính
### Authentication Component
- log in
- log in provider
- identity provider
- Hạ tầng quản lí truy cập và identity

### Component for requesting authenticated the users consent for delegation
Xuất hiện ngay sau cái Authentication Component. Sau khi bạn đã login nó sẽ hiện ra là bạn có thật sự muốn cung cấp những thông tin này
cho app thứ 3 không

### Hạ tầng quản lí token
Thực chất là database chứa token đã được sinh ra 

## Resources Owner
Thường là người dùng

## Third-app party
app bên thứ 3

## Resources Server
Nơi lưu trữ và quản lí Resource

# OAUth Endpoint
Có 4 loại
- Authorization Endpoint
- Token Endpoint
- Redirect Endpoint 
- Resources Endpoint 

## Authorization Endpoint
Người dùng gửi các input lên để lấy về authorization code và token
- Input Query 
  + State
  + Scope
  + response type 
  + client_id
  + rediect uri 
  
- Output 
  + Authorization code 
  + Access token 
  
## Token Endpoint
bên resource server gửi input lên bao gồm
- Input Query
  + State
  + Scope
  + Code

## Resource Endpoint
Nhận access token và refresh token 

# Các loại token và code
- Access token: để truy cập vào resources provider
- Refresh token: để tạo ra access token
- Authorization code để resources provider gửi cho client xác nhận rằng mày đã okke để gửi vào


  
  
  
  
  
  
  
  
  
