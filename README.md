<!DOCTYPE html>
<html lang="vi">
<head>
	<		.container {
			max-width: 1200px;
			margin: 40px auto;
			background: #111;
			border-radius: 16px;
			box-shadow: 0 4px 24px rgba(0,0,0,0.2);
			padding: 32px 24px;
			position: relative;
			overflow: hidden;
		}
		.container::before {
			content: '';
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 4px;
			background: linear-gradient(to right, #1a1a1a, #333);
		}
		h1 {
			text-align: center;
			color: #fff;
			font-size: 2em;
			margin-bottom: 32px;
			letter-spacing: 1px;
		}
		   .device-list {
			   display: grid;
			   grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
			   gap: 24px;
			   padding: 0 8px;
		   }vice-img {
			   width: 120px;
			   height: 90px;
			   background: #1a1a1a;
			   border-radius: 8px;
			   margin-bottom: 0;
			   margin-right: 16px;
			   display: flex;
			   align-items: center;
			   justify-content: center;
			   flex-shrink: 0;
			   overflow: hidden;
		   }
		   .device-img img {
			   width: 100%;
			   height: 100%;
			   object-fit: cover;
			   object-position: center;
			   border-radius: 8px;
			   transition: transform 0.3s ease;
		   }
		   .device-img:hover img {
			   transform: scale(1.05);
		   }name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
	<meta name="theme-color" content="#111111">
	<title>H248 Equipment Rental - Cho thuê thiết bị</title>
	<style>
		.contact-icon {
			stroke-width: 1.5;
			width: 20px;
			height: 20px;
			vertical-align: middle;
			margin-right: 8px;
		}
		* {
			font-family: 'Josefin Sansz', monospace !important;
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
			   gap: 20px;
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
			   min-width: 350px;
			   max-width: 350px;
			   width: 100%;
			   transition: box-shadow 0.2s;
		   }
		   .device-img {
			   width: 90px;
			   height: 90px;
			   background: #1a1a1a;
			   border-radius: 8px;
			   margin-bottom: 0;
			   margin-right: 16px;
			   display: flex;
			   align-items: center;
			   justify-content: center;
			   flex-shrink: 0;
			   overflow: hidden;
		   }
		   .device-img img {
			   width: 100%;
			   height: 100%;
			   object-fit: contain;
			   border-radius: 8px;
			   transition: transform 0.3s ease;
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
			font-size: 0.88em;
			color: #fff;
			font-weight: thin;
			margin-bottom: 4px;
		}
		.device-accessory {
			font-size: 0.73em;
			color: #ddd;
			margin-bottom: 0;
			text-align: left;
		}
		@media (max-width: 768px) {
			.container { 
				padding: 24px 16px;
				margin: 20px 12px;
				border-radius: 12px;
			}
			.device-list { 
				grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
				gap: 16px;
			}
			.device { 
				width: calc(100% - 16px);
				margin: 8px;
				min-width: unset;
			}
			header > div {
				padding: 0 12px;
			}
			header img {
				height: 100px !important;
				margin-right: 12px !important;
			}
			.contact-icon {
				width: 16px;
				height: 16px;
			}
			header div[style*="color: #fff"] {
				font-size: 0.9em;
			}
			header div[style*="margin-bottom: 8px"] {
				margin-bottom: 6px !important;
			}
		}

		@media (max-width: 480px) {
			.container { 
				margin: 16px 8px;
				padding: 20px 12px;
				border-radius: 10px;
			}
			.device {
				padding: 8px;
				margin: 6px;
			}
			.device-img {
				width: 140px;
				height: 100px;
				margin-right: 12px;
				padding: 3px;
			}
			.device-img img {
				width: 100%;
				height: 100%;
				object-fit: contain;
			}
			.device-title {
				font-size: 0.95em;
			}
			.device-price {
				font-size: 0.9em;
			}
			.device-accessory {
				font-size: 0.85em;
			}
			header img {
				height: 80px !important;
				margin-right: 8px !important;
			}
			header div[style*="color: #fff"] {
				font-size: 0.85em;
			}
			footer {
				font-size: 0.9em !important;
				padding: 14px 0 10px 0 !important;
			}
		}
	</style>
</head>
<body>
	<header style="padding: 20px 0; background: #111; box-shadow: 0 4px 18px rgba(0,0,0,0.10); margin-bottom: 18px;">
		<div style="max-width: 900px; margin: 0 auto;">
			<div style="display: flex; flex-direction: row; align-items: center; justify-content: space-between; padding: 0 20px;">
				<img src="LOGO/1x/FW.png" alt="Boom mic.jpg" style="height: 200px; margin-right: 24px; display: block;">
				<div style="color: #fff;">
					<div style="margin-bottom: 8px;">
						<svg xmlns="http://www.w3.org/2000/svg" class="contact-icon" style="stroke: #fff;" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round">
							<path stroke="none" d="M0 0h24v24H0z" fill="none"/>
							<path d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2" />
						</svg>
						<a href="tel:0395413371" style="color: #fff; text-decoration: none;">0395413371 / 0347041474</a>
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
					   <div class="device-price">300.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 2 x pin FZ50, 1 x Thẻ nhớ 64G</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="RS4.jpg" alt="RS4"></div>
				   <div class="device-info">
					   <div class="device-title">DJI Ronin RS4</div>
					   <div class="device-price"> 350.000 VNĐ/ngày</div> 
					   <div class="device-accessory">Phụ kiện: 1 x tay ngang, 1 x cable type C</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="18-105mm.jpg" alt="Lens 18-105mm"></div>
				   <div class="device-info">
					   <div class="device-title">Lens Sony 18-105mm F4</div>
					   <div class="device-price">200.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: filter chống bụi</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Comica VM30.webp" alt="Comica VM30"></div>
				   <div class="device-info">
					   <div class="device-title">Micro Comica VM30</div>
					   <div class="device-price">200.000 VNĐ/ngày</div>
					   <div class="device-accessory">Phụ kiện: 1 x dây micro sang XRL</div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Tripod Triopo.webp" alt="Tripod Triopo"></div>
				   <div class="device-info">
					   <div class="device-title">Tripod Triopo</div>
					   <div class="device-price">80.000 VNĐ/ngày</div>
					   <div class="device-accessory"></div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Boom mic.jpg" alt="Gimbal DJI Ronin S4"></div>
				   <div class="device-info">
					   <div class="device-title">Cần boom 3m</div>
					   <div class="device-price">100.000 VNĐ/ngày</div>
					   <div class="device-accessory"></div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Đèn cầm tay.jpg" alt="Đèn Led NANlite Forza 60B Bi Color"></div>
				   <div class="device-info">
					   <div class="device-title">Đèn Led cầm tay</div>
					   <div class="device-price">50.000 VNĐ/ngày</div>
					   <div class="device-accessory"></div>
				   </div>
			   </div>
			   <div class="device">
				   <div class="device-img"><img src="Hắt sáng.jpg" alt="Microphone Rode Wireless Go II"></div>
				   <div class="device-info">
					   <div class="device-title">Hắt sáng</div>
					   <div class="device-price">20.000 VNĐ/ngày</div>
					   <div class="device-accessory"></div>
				   </div>
			   </div>
		</div>
	</div>
	<footer style="margin-top: 32px; background: #111; color: #fff; text-align: center; padding: 18px 0 12px 0; font-size: 1em;">
		© 2025 · H248 Equipment Rental · Hieu KL
</body>
</html>
