# Introduction

# Pros/Cons

# Documentation

- [Tài liệu chính thức](https://nuxtjs.org/)
- [Github](https://github.com/nuxt/nuxt.js)
- [Nuxt awesome](https://github.com/nuxt-community/awesome-nuxt)
- Khóa học
- Tài liệu
...

# [Install](https://nuxtjs.org/guide/installation)

### Create Nuxt.js app
npm install
npm install -g create-nuxt-app
create-nuxt-app project_name ->....

# [Folder structure](https://nuxtjs.org/guide/directory-structure)


- `Assets`: Thư mục này là nơi chứa tất cả các file chưa được compile như Sass, Less, ... Ở đây chúng ta có thể thêm các file chứa css template.
- `Components`: Nơi chứa các thành phần mà chúng ta phân chia trong ứng dụng
- `Layouts`: Chứa các master layout của ứng dụng, chẳng hạn như: header, sidebar...
- `Middleware`: Giống như các ngôn ngữ phía server, middleware ở đây cho phép chúng ta tùy biến các function được thực thi trước khi các page được render.
- `Pages`: Đây là thành phần bắt buộc duy nhất(các folder khác ko có cũng ko sao). Nó chứa các views và route của ứng dụng. Ở đây Nuxt sẽ đọc tất các các file *.vue bên trong thư mục và tự động tạo thành route cho chúng ta. Hiểu đơn giản nó dạng tree với root domain là '/', các route khác: '/{folder_name|file_name}'. Chúng ta sẽ nói chi tiết ở phần dưới.
- `Plugins`: Nơi chứa các JS plugin và sẽ được chạy trước khi Vuejs khởi tạo.
- `Static`: Nó gần giống assets folder, nhưng ở đây chứa các file ít thay đổi, kiểu như: logo.png, favicon, robots.txt. Đường dẫn tới file sẽ là: "/logo.png"
- `Store`: Mặc định Nuxt đã có sẵn VueX, và thư mục này chứa vuex store files.
- `Config.nuxt.js`: File chứa các cấu hình của ứng dụng. Khi mọi thứ được config ở đây sẽ được sử dụng global. Các config như: Loading, plugin, env, route, ...


# Basic

### Routing https://nuxtjs.org/guide/routing
### Views
### Pages
### Middleware & Authentication
### Assets, static, style
### Module
### Vuex
### Async data
https://nuxtjs.org/guide/async-data
### Plugin
### Config
### API (All basic) https://nuxtjs.org/api/

# Code demo and more
npm run dev | nuxt
nuxt build
nuxt start
# build html
npm generate

# Production

# Author:

[Bùi Huy Cường](https://medium.com/@buihuycuong)