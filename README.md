<button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="blueberry.jpg" alt="Kem Việt Quất">
                    <h3>Kem Việt Quất</h3>
                    <p>Giá: 35,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="raspberry.jpg" alt="Kem Mâm Xôi">
                    <h3>Kem Mâm Xôi</h3>
                    <p>Giá: 32,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="toffee.jpg" alt="Kem Kẹo Bơ">
                    <h3>Kem Kẹo Bơ</h3>
                    <p>Giá: 38,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="peach.jpg" alt="Kem Đào">
                    <h3>Kem Đào</h3>
                    <p>Giá: 30,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="cookies.jpg" alt="Kem Bánh Quy">
                    <h3>Kem Bánh Quy</h3>
                    <p>Giá: 33,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="caramel.jpg" alt="Kem Caramel">
                    <h3>Kem Caramel</h3>
                    <p>Giá: 37,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="passionfruit.jpg" alt="Kem Chanh Leo">
                    <h3>Kem Chanh Leo</h3>
                    <p>Giá: 34,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
                <div class="product">
                    <img src="taro.jpg" alt="Kem Khoai Môn">
                    <h3>Kem Khoai Môn</h3>
                    <p>Giá: 36,000 VND</p>
                    <button>Thêm vào Giỏ</button>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Liên Hệ</h2>
            <p>Địa chỉ: 31/8 Nguyễn Bĩnh Khiêm, Thành phố Vũng Tàu</p>
            <p>Email: thonghoang12005@gmail.com</p>
            <p>Số điện thoại: 0383-704-182</p>
        </section>

        <section id="cart">
            <h2>Giỏ Hàng</h2>
            <p>Hiện tại không có sản phẩm nào trong giỏ hàng của bạn.</p>
        </section>

        <footer>
            <p>&copy; 2024 Cửa Hàng Kem Ngon. Tất cả quyền lợi được bảo lưu.</p>
        </footer>
    </div>

    <script>
        function showProducts(page) {
            document.getElementById('page1').classList.add('hidden');
            document.getElementById('page2').classList.add('hidden');

            document.getElementById(page).classList.remove('hidden');
        }
    </script>
</body>
</html>
