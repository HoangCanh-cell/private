<!DOCTYPE html>
<html>
    <link rel="stylesheet" type="text/css" href="style.css">
    <body>
        <header>
            <div class="container">
            </div>
        </header>
        <main>
            <div class="container">
                <div class="register-form">
                    <form action="" method="post">
                        <h1>Đăng ký tài khoản mới</h1>
                        <div class="input-box">

                            <input type="text" placeholder=" username">
                        </div>
                        <div class="input-box">

                            <input type="password" placeholder=" mật khẩu">
                        </div>
                        <div class="input-box">
                            <div class="col-6">
                                <label for="ngaysinh">Ngày sinh</label>
                                  <br>
                                <input type="date" id="ngaysinh"/>

                            </div>
                            <div class="col-6">
                                <label for="gioitinh">Giới tính</label>
                                <br>
                                <select id="gioitinh">
                                    <option value="nam">Nam</option>
                                    <option value="nu">Nữ</option>
                                </select>
                            </div>
                            <div class="clear"></div>
                        </div>
                        <div class="input-box">
                            <span>Sở thích</span>
                            <br>
                            <input type="checkbox" id="xemphim" checked=""> 
                            <label for="xemphim">Xem phim</label>
                            <div class="margin_b"></div>
                            <input type="checkbox" id="nghenhac"> 
                            <label for="nghenhac">Nghe nhạc</label>
                            <div class="margin_b"></div>
                            <input type="checkbox" id="docsach"> 
                            <label for="docsach">Đọc sách</label>
                        </div>
                        <div class="input-box">
                            <label for="gioithieu">Note</label>
                            <br>
                            <textarea id="gioithieu"></textarea>
                        </div>
                        
                        <div class="btn-box">
                            <button type="submit">
                                Đăng ký
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </main>
     
    </body>
</html>
