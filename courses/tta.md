---
title: Các lớp Toán Tiếng Anh
layout: default
image: "/assets/img/dapp.png"
---

<style>
    .hero-section, .features-section, .quote-section, .blog-section {
        padding: 30px 0;
        border-radius: 2px;
    }
    
    .features-section * {
        box-sizing: border-box;
    }
    
    
    .features-section .feature-row {
        display: flex;
        justify-content: space-evenly;
        flex-wrap: wrap;
    }
    
    .features-section .feature-row .feature-card {
        background-color: #fff;
        /*width: 238.65px;*/
        width: calc(33.333% - 8px);
        margin-top: 16px;
        border-radius: 2px;
        box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 3px 1px -2px rgba(0,0,0,.2), 0 1px 5px 0 rgba(0,0,0,.12);
    }
    
    .features-section .feature-row .feature-card .image {
        background-color: rgb(43, 180, 201);
        background-size: cover;
        background-position: center;
        min-height: 4px;
    }
    
    .features-section .feature-row .feature-card .text {
        padding: 32px 16px;
    }
    
    .features-section h5 {
        color: #111;
        font-size: 21px;
    }
    
    .features-section p {
        color: #828282;
        font-size: 90%;
        padding-top: 12px;
        margin-bottom: 0;
    }

    .features-section .feature-row .feature-card.course:first-of-type {
        background-color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:nth-of-type(2) {
        background-color: rgb(201,180,43);
    }

    .features-section .feature-row .feature-card.course:last-of-type {
        background-color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.course .image {
        background-color: transparent;
    }

    .features-section .feature-row .feature-card.course .image h5 {
        background-color: #fff;
        color: rgb(201,180,43);
        position: relative;
        top: 4px;
        left: 2px;
        display: inline;
        padding: 6px 8px;
    }

    .features-section .feature-row .feature-card.course:first-of-type .image h5 {
        color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:last-of-type .image h5 {
        color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.course .text p {
        color: #f8f8f8;
    }

    .features-section .feature-row .feature-card.course .button a {
        color: #fff;
        border: 1px solid #f8f8f8;
        padding: 6px 16px;
    }
    .features-section .feature-row .feature-card.course .button a:visited {
        color: #fff;
    }
    .features-section .feature-row .feature-card.course .button a:hover {
        text-decoration: none;
        background-color: #fff;
        color: rgb(201,180,43);
    }
    .features-section .feature-row .feature-card.course:first-of-type .button a:hover {
        color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:last-of-type .button a:hover {
        color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.portrait .image {
        height: 192px;
        background-color: #333;
        position: relative;
    }

    .features-section .feature-row .feature-card.portrait .image h5 {
        color: #f8f8f8;
        background-color: rgb(43, 180, 201);
        display: inline-block;
        padding: 0 8px;
        position: absolute;
        bottom: -24px;
    }

    .features-section .feature-row .feature-card.portrait .text {
        padding: 8px 16px 28px;
    }
    
    .features-section .feature-row .feature-card .button {
        padding: 16px 16px 32px;
    }
    
    .quote-section {
        background-color: rgb(241, 241, 240);
        background-image: url("/assets/img/pattern1.png");
    }
    
    figure.testimonial {
        position: relative;
        float: left;
        margin: 10px 1% 40px;
        max-width: 480px;
        width: 100%;
        color: #333;
        text-align: left;
        border-radius: 90px;
        box-shadow: -3px 5px 12px 0 rgba(0,0,0,0.3);
    }
    figure.testimonial.first {
        transform: rotate(-5deg);
        top: 18px;
    }
    figure.testimonial.second {
        float:right;
        transform: rotate(15deg);
    }
    figure.testimonial * {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
    }
    figure.testimonial img {
        float: right;
        max-width: 40%;
        vertical-align: middle;
        background-color: rgb(107, 101, 91);
        /*border-radius: 0 8px 8px 0;*/
    }
    figure.testimonial figcaption {
        top: 0;
        bottom: 0;
        left: 0;
        width: 60%;
        position: absolute;
        background-color: #fdf9c5;
        border-radius: 8px 0 0 8px;
    }
    figure.testimonial blockquote {
        background-color: #fdf9c5;
        position: relative;
        padding: 25px 50px 25px 50px;
        font-size: 0.9em;
        font-weight: 500;
        text-align: left;
        margin: 0;
        line-height: 1.6em;
        font-style: italic;
        border-left: 0;
        color: #333;
    }
    figure.testimonial blockquote:before,
    figure.testimonial blockquote:after {
        font-family: 'FontAwesome';
        content: "\201C";
        position: absolute;
        font-size: 50px;
        opacity: 0.3;
        font-style: normal;
    }
    figure.testimonial blockquote:before {
        top: 25px;
        left: 20px;
    }
    figure.testimonial blockquote:after {
        content: "\201D";
        right: 20px;
        bottom: 0px;
    }
    figure.testimonial .arrow {
        top: 30px;
        left: 100%;
        width: 0;
        height: 0;
        border-left: 0 solid transparent;
        border-right: 25px solid transparent;
        border-top: 25px solid #fdf9c5;
        margin: 0;
        position: absolute;
    }
    figure.testimonial .author {
        position: absolute;
        top: 100%;
        width: 100%;
        padding: 10px 15px;
        color: #333;
        margin: 0;
        text-transform: uppercase;
    }
    figure.testimonial .author h5 {
        opacity: 0.8;
        margin: 0;
        font-weight: 800;
    }
    figure.testimonial .author h5 span {
        font-weight: 400;
        text-transform: none;
        padding-left: 5px;
    }
    
    @media only screen and (max-width: 700px) {
        .features-section .feature-row .feature-card {
            width: 48%;
        }
    }
    @media only screen and (max-width: 460px) {
        .features-section .feature-row .feature-card {
            width: 100%;
        }
        figure.testimonial.first {
            top: 32px;
        }
        figure.testimonial.first .author {
            top: auto;
            bottom: 100%;
        }
    }
    
    @media only screen and (max-width: 499px) {
        figure.testimonial img {
            display: none;
        }
        figure.testimonial figcaption {
            width: 100%;
            position: relative;
        }
        figure.testimonial.second {
            float:left;
        }
        figure.testimonial .arrow {
            display: none;
        }
        figure.testimonial.first blockquote {
            text-align: right;
        }
    }
    
    .hero-section {
        text-align: center;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        padding: 60px 4.5% 48px;
    }
    
    .hero-section h1 {
        font-size: 28px;
        font-weight: 500;
        color: #111;
    }
    
    .hero-section h3 {
        color: #333;
        font-weight: 300;
    }
    
    .hero-section .action-zone {
        padding: 32px 0;
    }
    
    .hero-section a.main-button {
        color: #f5f5f5;
        background-color: #15B5DD;
        text-decoration: none;
        padding: 16px 24px;
        border-radius: 2px;
    }
    
    .hero-section a.main-button:hover {
        color: #fff;
    }
    
    h2.section-title {
        font-weight: 300;
        text-transform: uppercase;
        text-align: center;
        color: #828282;
    }
</style>
<section class="hero-section">
    <div style="text-align: center;font-size:0.9rem;color:#333;font-weight:300">Khoá học</div>
    <h1>Ethereum DApp Development</h1>
    <h3>Tự tin làm bất kỳ DApp nào cho các blockchain tương thích Ethereum</h3>
    <div class="action-zone">
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSe69bVLIUWTGkTmed1p3VPIpFFee1eBPyndf_gSp65YCy4Mhg/viewform" class="main-button">ĐĂNG KÍ →</a>
    </div>
    <div>
        Trao đổi: <a href="mailto:thi@trada.tech" target="_blank">Email</a> - <a href="https://t.me/mangcut" target="_blank">Telegram</a>
    </div>
</section>

<!--
<p style="margin-bottom:0"><i>Khoá học</i></p>
## Ethereum DApp Development
<p><a href="mailto:thi@trada.tech" target="_blank">Email</a> - <a href="https://t.me/mangcut" target="_blank">Telegram</a> - <a href="https://docs.google.com/forms/d/e/1FAIpQLSe69bVLIUWTGkTmed1p3VPIpFFee1eBPyndf_gSp65YCy4Mhg/viewform" target="_blank">Đăng kí</a></p>
-->

<style>
    .key-info {
        list-style: none;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
    }
    .key-info li {
        display: inline-block;
        padding: 18px 18px 3px;
        border-bottom: 2px solid #15B5DD;
        color: #15B5DD;
    }
    .blog-section {
        padding: 24px 18px 12px;
        margin-top: 2rem;
    }
    .blog-section h3 {
        text-transform: uppercase;
    }
    .blog-section ul {
        list-style: none; /* Remove default bullets */
    }

    .blog-section ul li::before {
        content: "\2022";  /* Add content: \2022 is the CSS Code/unicode for a bullet */
        color: #15B5DD; /* Change the color */
        font-weight: bold; /* If you want it to be bold */
        display: inline-block; /* Needed to add space between the bullet and the text */ 
        width: 1em; /* Also needed for space (tweak if needed) */
        margin-left: -1em; /* Also needed for space (tweak if needed) */
    }
</style>
<ul class="key-info">
    <li>5 tuần</li>
    <li>2 buổi/tuần</li>
    <li>2 tiếng/buổi</li>
    <li>Học ngoài giờ</li>
</ul>

<br><br>

<div class="blog-section" style="background:#eee">
    <h2 class="section-title">Đầu ra là 1 DApp hoàn thiện</h2>
    <ul>
        <li>Chủ đề của DApp theo đề xuất của học viên (mạng xã hội, chat app, game, v.v.)</li>
        <li>Hệ thống smart contract viết bằng Solidity</li>
        <li>Có phát hành token riêng</li>
        <li>Tích hợp uPort để quản lý danh tính</li>
        <li>Tích hợp IPFS để lưu photo</li>
        <li>Client tích hợp MetaMask, Web3 JS</li>
        <li>Phát triển, debug, và test bằng Truffle và Ganache</li>
    </ul>
</div>

<div class="blog-section">
    <h2 class="section-title">Sau khoá học bạn sẽ</h2>
    <ul>
        <li>Hiểu bản chất, cơ chế hoạt động, xu hướng sắp tới của blockchain</li>
        <li>Nắm được ưu điểm, bất cập, các ứng dụng phù hợp với blockchain</li>
        <li>Tự tin viết smart contract bằng Solidity</li>
        <li>Thực hành Web3 JS, tích hợp IPFS, uPort</li>
        <li>Thạo tool: MetaMask, EthFiddle, Remix, Truffle, Ganache</li>
        <li>Có kiến thức về coding an toàn và tối ưu phí giao dịch</li>
        <li>Có trải nghiệm để cân nhắc mức độ áp dụng blockchain hợp lý</li>
        <li>Có căn bản để tự tìm hiểu khi gặp vấn đề ngoài những thứ đã học</li>
        <li>Tự tin thảo luận giải pháp cho bài toán mới</li>
    </ul>
    <p><i>Dĩ nhiên, bạn phải rèn luyện và làm thêm nhiều dự án thực để rèn sắc kỹ năng của mình. Các giảng viên của Trada Academy luôn sẵn sàng trả lời câu hỏi và đồng hành trong suốt quãng thời gian sau này.</i></p>
</div>

<section class="features-section">	
    <h2 class="section-title">Giảng viên</h2>
    <div class="features-wrapper">
        <div class="feature-row">
            <div class="feature-card portrait">
                <div class="image" style="background-image:url(/assets/img/thi.jpg)">
                    <h5>Thi măng cụt</h5>
                </div>
                <div class="text">
                    <p>Founder of Trada Tech, former manager and blockchain trainer of Kyber Network.</p>
                </div>
            </div>
            <div class="feature-card portrait">
                <div class="image" style="background-image:url(/assets/img/andrew.jpg)">
                    <h5>Andrew Nguyen</h5>
                </div>
                <div class="text">
                    <p>Technical Manager of Kyber Network, technical lead of KyberSwap.</p>
                </div>
            </div>
            <div class="feature-card portrait">
                <div class="image" style="background-image:url('http://en.sotatek.com/wp-content/themes/sotatek/images/network_effect/an.png')">
                    <h5>Andy Nguyen</h5>
                </div>
                <div class="text">
                    <p>Co-founder and Blockchain lead of Sotatek.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<div class="blog-section" style="background:#eee">
    <h2 class="section-title">Học phí</h2>
    <ul>
        <li>10 triệu/học viên</li>
        <li>Giảm 10% nếu đăng kí trước 1 tuần</li>
        <li>Giảm thêm 20% cho công ty hoặc nhóm từ 3 người trở lên</li>
        <li>Lớp riêng cho công ty: 50 triệu/lớp (tối đa 10 người)</li>
    </ul>
</div>

<div class="blog-section">
    <h2 class="section-title">Yêu cầu với học viên</h2>
    <ul>
        <li>Đã lập trình tự tin với 1 ngôn ngữ/công nghệ bất kì</li>
        <li>Có hứng thú học về blockchain</li>
        <li>Có thái độ học tập nghiêm túc</li>
    </ul>
    <p>Học viên cần đi học đều và hỏi nhiều. Làm bài tập về nhà. Khoá học ít dùng slide mà dựa vào giảng giải trực tiếp và live code, nên bạn cần tham gia sâu vào quá trình học chứ không trông đợi đọc slide.</p>
</div>

<div class="blog-section" style="background:#eee">
    <h2 class="section-title">Lịch học cụ thể</h2>
    <p>Học trong 10 buổi, từ 7pm~9pm hoặc cuối tuần (tuỳ khoá).</p>
    <h3>Buổi 1: Lý thuyết Blockchain và Ethereum</h3>
    <ul>
        <li>Tại sao cần blockchain</li>
        <li>Nó hoạt động thế nào</li>
        <li>Ưu nhược điểm</li>
        <li>Use cases</li>
        <li>Các vấn đề cần giải quyết</li>
        <li>Cơ chế hoạt động của Ethereum</li>
    </ul>
    <h3>Buổi 2: Live code & Thực hành</h3>
    <ul>
        <li>Tạo 1 blockchain từ đầu bằng JavaScript</li>
    </ul>
    <h3>Buổi 3: Solidity cơ bản - thực hành trên EthFiddle</h3>
    <ul>
        <li>Contract</li>
        <li>Types and Variables</li>
        <li>Struct & Array</li>
        <li>Function</li>
        <li>Modifier</li>
        <li>Control flow</li>
        <li>Tương tác: tạo 1 Zombie!</li>
    </ul>
    <h3>Buổi 4: Remix & Web3 JS</h3>
    <ul>
        <li>Tạo, debug, và test contract bằng Remix</li>
        <li>Dùng Web3 JS để tương tác với contract vừa tạo</li>
    </ul>
    <h3>Buổi 5: Truffle và Zeppelin</h3>
    <ul>
        <li>Cài đặt và sử dụng Truffle</li>
        <li>Giới thiệu về các thư viện Zeppelin</li>
        <li>Tạo 1 token contract</li>
    </ul>
    <h3>Buổi 6: Token sale</h3>
    <ul>
        <li>Tạo token sale contract bằng truffle</li>
        <li>Viết front-end token sale dùng Web3 JS</li>
    </ul>
    <h3>Buổi 7: Làm dự án phần 1</h3>
    <ul>
        <li>Chia team</li>
        <li>Bầu chọn sản phẩm sẽ làm</li>
        <li>Làm sản phẩm buổi 1</li>
    </ul>
    <h3>Buổi 8: Làm dự án phần 2</h3>
    <ul>
        <li>Các bài học về security</li>
        <li>Làm sản phẩm buổi 2</li>
    </ul>
    <h3>Buổi 9: Làm dự án phần 3</h3>
    <ul>
        <li>Các tips về tiết kiệm gas</li>
        <li>Làm sản phẩm buổi 3</li>
    </ul>
    <h3>Buổi 10: Hoàn thiện sản phẩm</h3>
    <ul>
        <li>Review hoàn thiện sản phẩm</li>
        <li>Trình bày và đánh giá</li>
    </ul>
</div>

<div class="hero-section">
    <h2 class="section-title">Đăng kí</h2>
    <div class="action-zone">
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSe69bVLIUWTGkTmed1p3VPIpFFee1eBPyndf_gSp65YCy4Mhg/viewform" class="main-button">Google Form →</a>
    </div>
    <div>
        Trao đổi: <a href="mailto:thi@trada.tech" target="_blank">Email</a> - <a href="https://t.me/mangcut" target="_blank">Telegram</a>
    </div>
</div>
