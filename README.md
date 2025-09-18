<!DOCTYPE html>
<html lang="vi">
<head>
	<style>
		.contact-icon {
			stroke-width: 1.5;
			width: 20px;
			height: 20px;
			vertical-align: middle;
			margin-right: 8px;
		}
		* {
			font-family: 'Courier', monospace !important;
		}
		body {
			background: #000000;
			margin: 0;
			color: #000;
		}
		.container {
			max-width: 900px;
			margin: 32px auto;
			background: #111;
			border-radius: 8px;
			box-shadow: 0 2px 8px rgba(255,255,255,0.1);
			padding: 24px 12px;
		}
		h1 {
			text-align: center;
			color: #000;
			font-size: 2em;
			margin-bottom: 24px;
		}
		   .device-list {
			   display: flex;
			   flex-wrap: wrap;
			   gap: 18px;
			   justify-content: center;
		   }
		   .device {
			   background: #2a2a2a;
			   border-radius: 12px;
			   box-shadow: 0 2px 12px rgba(255,255,255,0.07);
			   padding: 10px 12px;
			   margin: 8px;
			   display: flex;
			   flex-direction: row;
			   align-items: center;
			   min-width: 260px;
			   max-width: 370px;
			   width: 100%;
			   transition: box-shadow 0.2s;
		   }
		   .device-img {
			   width: 90px;
			   height: 70px;
			   background: #e9ecf3;
			   border-radius: 5px;
			   margin-bottom: 0;
			   margin-right: 16px;
			   display: flex;
			   align-items: center;
			   justify-content: center;
			   flex-shrink: 0;
		   }
		   .device-img img {
			   width: 90px;
			   height: 70px;
			   object-fit: cover;
			   border-radius: 5px;
		   }
		   .device-info {
			   display: flex;
			   flex-direction: column;
			   align-items: flex-start;
			   flex: 1;
		   }
		.device-title {
			font-size: 1em;
			font-weight: bold;
			color: #fff;
			margin: 0 0 6px 0;
			text-align: left;
		}
		.device-price {
			font-size: 0.98em;
			color: #fff;
			font-weight: bold;
			margin-bottom: 4px;
		}
		.device-accessory {
			font-size: 0.93em;
			color: #ddd;
			margin-bottom: 0;
			text-align: left;
		}
		@media (max-width: 700px) {
			.container { padding: 6px; }
			.device-list { flex-direction: column; align-items: center; }
			.device { width: 100%; max-width: 320px; }
		}
	</style>
</head>
<body>
	<header style="padding: 20px 0; background: #111; box-shadow: 0 4px 18px rgba(0,0,0,0.10); margin-bottom: 18px;">
		<div style="max-width: 900px; margin: 0 auto;">
			<div style="display: flex; flex-direction: row; align-items: center; justify-content: space-between; padding: 0 20px;">
				<img src="FB.png" alt="FB.png" style="height: 140px; margin-right: 24px; display: block;">
				<div style="color: #fff;">
					<div style="margin-bottom: 8px;">
						<svg xmlns="http://www.w3.org/2000/svg" class="contact-icon" style="stroke: #fff;" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
							<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
							<path d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2" />
						</svg>
						<a href="tel:0395413371" style="color: #fff; text-decoration: none;">0395413371</a>
					</div>
					<div style="margin-bottom: 8px;">
						<svg xmlns="http://www.w3.org/2000/svg" class="contact-icon" style="stroke: #fff;" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
							<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
							<rect x="3" y="5" width="18" height="14" rx="2" />
							<polyline points="3 7 12 13 21 7" />
						</svg>
						<a href="mailto:h248production@gmail.com" style="color: #fff; text-decoration: none;">h248production@gmail.com
                        </a>
					</div>
					<div style="margin-bottom: 8px;">
						<svg xmlns="http://www.w3.org/2000/svg" class="contact-icon" style="stroke: #fff;" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
							<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
							<circle cx="12" cy="12" r="9" />
							<polyline points="12 7 12 12 15 15" />
						</svg>
						8:00 - 18:00
					</div>
					<div>
						<svg xmlns="http://www.w3.org/2000/svg" class="contact-icon" style="stroke: #fff;" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
							<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
							<circle cx="12" cy="11" r="3" />
							<path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
						</svg>
						Ngách 82/122, ngõ 166 Kim Mã, Ba Đình, Hà Nội
					</div>
				</div>
			</div>
		</div>
	</header>
	<div class="container">
		<div class="device-list">
			   <div class="device">
				   <div class="device-img"><img src="A6400.jpg" alt="Sony Alpha A6400"></div>
				   <div class="device-info">
					   <div class="device-title">Sony Alpha A6400</div>
					   <div class="device-price">500.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="RS4.jpg" alt="RS4"></div>
				   <div class="device-info">
					   <div class="device-title">DJI Ronin RS4</div>
					   <div class="device-price"> 11VNĐ/ngày</div> 
					   <div class="device-accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="18-105mm.jpg" alt="Lens 18-105mm"></div>
				   <div class="device-info">
					   <div class="device-title">Lens Sony 18-105mm F4</div>
					   <div class="device-price">600.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 2 x pin FZ100, 1 x Thẻ nhớ 64G</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Comica VM30.webp" alt="Comica VM30"></div>
				   <div class="device-info">
					   <div class="device-title">Micro Comica VM30</div>
					   <div class="device-price">300.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: Filter chống bụi</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Tripod Triopo.webp" alt="Tripod Triopo"></div>
				   <div class="device-info">
					   <div class="device-title">Tripod Triopo</div>
					   <div class="device-price">500.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 3 x pin, 1 x Thẻ nhớ 64G</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="DSC04261.JPG" alt="Gimbal DJI Ronin S4"></div>
				   <div class="device-info">
					   <div class="device-title">Gimbal DJI Ronin S4</div>
					   <div class="device-price">350.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: Cable type C</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="328C79CF-047A-4029-8839-FA5AF6F80723.jpeg" alt="Đèn Led NANlite Forza 60B Bi Color"></div>
				   <div class="device-info">
					   <div class="device-title">Đèn Led NANlite Forza 60B Bi Color</div>
					   <div class="device-price">250.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 1 x Chân đèn</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="CE881EEA-6E8E-46EC-AC38-2D5ABA394858.jpeg" alt="Microphone Rode Wireless Go II"></div>
				   <div class="device-info">
					   <div class="device-title">Microphone Rode Wireless Go II</div>
					   <div class="device-price">300.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 2 x TX, 1 x RX, Cable SC2</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="DSC04261.JPG" alt="Monitor Ninja V"></div>
				   <div class="device-info">
					   <div class="device-title">Monitor Ninja V (ngừng cung cấp)</div>
					   <div class="device-price">350.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: Nguồn, 2 x Pin F970</div>
				   </div>
			   </div>
		</div>
	</div>
	<footer style="margin-top: 32px; background: #111; color: #fff; text-align: center; padding: 18px 0 12px 0; font-size: 1em;">
		© 2025 · H248 Equipment Rental | Hotline: 0395413371
	</footer>
</body>
</html>
