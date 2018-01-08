
# Giới thiệu
1. VueJS Gọi tắt là Vue gọi tắt giống View  trong tiếng anh.
2. Vue là một Javascript Framework linh động dùng để xây dung thiết kế xây dựng gia diện người dùng (UI)
3. Tính đến thời điểm hiện tại thì VueJS đã cho ra 4 version khác nhau và cao nhất là version 2.3.4. Các version đó là:

    •	VueJS 0.11
    •	VueJS 0.12
    •	VueJS 1.0
    •	VueJS 2.x
# Cài đặt
1. Download
    Mỗi version của Vue sẽ có hai phiên bản, một dành cho nhà phát triển (lập trình viên)  hay còn gọi là (development), vmột dành cho sản phẩm đã hoàn thiện (production). Điều này tương tự như jQuery bạn sẽ có 2 file, một file đã được nén gọn và một file chưa nén gọn.
    
    Phiên bản development: https://vuejs.org/js/vue.js
    
    Phiên bản production: https://vuejs.org/js/vue.min.js
2. Import Vue bằng CND :
    Nếu bạn không muốn rườm rà thì có thể sử dụng đường link trực tiếp từ trang chủ của nó, với cách này bạn chỉ việc copy đường link và chèn vào mã nguồn website của bạn là xong. Với cách này thì có ưu điểm là mã nguồn của Vue sẽ luôn được cập nhật mới, tuy nhiên sẽ có nhược điểm là phụ thuộc vào tốc độ của mạng.
3. Khả năng tương thích: 
    Do sử dụng một số tính năng ECMAScript 5 không được hỗ trợ trên IE8, Vue không hỗ trợ IE8 và các phiên bản thấp hơn. Tuy nhiên Vue hỗ trợ mọi trình duyệt tương thích với ECMAScript 5.
4. Debug :
    add-on Vue Devtools vào trình duyệt. Add-on này giúp bạn kiểm tra và debug (kiểm lỗi) ứng dụng Vue 
    https://github.com/vuejs/vue-devtools#vue-devtools
5. Cài đặt npm :         
       
        $ npm install vue
6. Cài đặt CLI :
    Vue.js cung cấp một CLI giúp nhanh chóng khởi tạo nền tảng (scaffolding) cho các ứng dụng một trang. Vue-CLI chuẩn bị sẵn các cài đặt phong phú cho một quy trình front-end hiện đại. Chỉ mất vài phút, bạn đã có thể bắt đầu xây dựng ứng dụng với các tính năng như hot-reload, tinh chỉnh code khi save (lint-on-save), và các bản build sẵn sàng để deploy lên production.
        
        # cài đặt vue-cli
        $ npm install --global vue-cli
        # tạo một dự án mới với template "webpack"
        $ vue init webpack my-project
        # cài đặt các thư viện phụ thuộc và bắt tay vào việc!
        $ cd my-project
        $ npm install
        $ npm run dev
