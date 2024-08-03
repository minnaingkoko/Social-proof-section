<script>
	import top from '$lib/images/bg-pattern-top-desktop.svg';
	import top_alt from '$lib/images/bg-pattern-top-mobile.svg'
	import star from '$lib/images/icon-star.svg';
	import bottom from '$lib/images/bg-pattern-bottom-desktop.svg';
	import bottom_alt from '$lib/images/bg-pattern-bottom-mobile.svg'
	import img1 from '$lib/images/image-colton.jpg';
	import img2 from '$lib/images/image-irene.jpg';
	import img3 from '$lib/images/image-anne.jpg';
</script>

<img class="top-abso" src={top} alt="" />
<img class="top-abso-alt" src={top_alt} alt="" />
<div class="container">
	<div class="row1">
		<div class="left">
			<h1 class="heading">10,000+ of our users love our products.</h1>
			<div class="text">
				We only provide great products combined with excellent customer service. See what our
				satisfied customers are saying about our services.
			</div>
		</div>
		<div class="right">
			<div class="r1">
				<div class="star-row">
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
				</div>
				<div class="r-text">Rated 5 Stars in Reviews</div>
			</div>
			<div class="r2">
				<div class="star-row">
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
				</div>
				<div class="r-text">Rated 5 Stars in Report Guru</div>
			</div>
			<div class="r3">
				<div class="star-row">
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
					<img src={star} alt="" />
				</div>
				<div class="r-text">Rated 5 Stars in BestTech</div>
			</div>
		</div>
	</div>
	<div class="row2">
		<div class="col1">
			<div class="profile">
				<img class="pro-img" src={img1} alt="" />
				<div class="col">
					<div class="name">Colton Smith</div>
					<div class="status">Verified Buyer</div>
				</div>
			</div>
			<div class="pro-text">
				“ We needed the same printed design as the one we had ordered a week prior. Not only did
				they find the original order, but we also received it in time. Excellent! ”
			</div>
		</div>
		<div class="col2">
			<div class="profile">
				<img class="pro-img" src={img2} alt="" />
				<div class="col">
					<div class="name">Irene Roberts</div>
					<div class="status">Verified Buyer</div>
				</div>
			</div>
			<div class="pro-text">
				“ Customer service is always excellent and very quick turn around. Completely delighted with
				the simplicity of the purchase and the speed of delivery.”
			</div>
		</div>
		<div class="col3">
			<div class="profile">
				<img class="pro-img" src={img3} alt="" />
				<div class="col">
					<div class="name">Anne Wallace</div>
					<div class="status">Verified Buyer</div>
				</div>
			</div>
			<div class="pro-text">
				“ Put an order with this company and can only praise them for the very high standard. Will
				definitely use them again and recommend them to everyone! ”
			</div>
		</div>
	</div>
</div>
<img class="bottom-abso" src={bottom} alt="" />
<img class="bottom-abso-alt" src={bottom_alt} alt="" />

<style>
	.top-abso {
		position: absolute;
		top: 0;
		left: 0;
	}
	.top-abso-alt { 
		display: none;
	}
	.container {
		margin-top: 118px;
	}
	.row1 {
		width: 1110px;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
	}
	.heading {
		width: 445px;
		font-size: 56px;
		line-height: 48px;
		letter-spacing: -2px;
		font-weight: bold;
		margin-bottom: 16px;
		color: #512051;
	}
	.text {
		font-size: 19px;
		width: 445px;
		line-height: 25px;
		font-weight: 500;
		color: #927b91;
		letter-spacing: -0.63px;
		margin-bottom: 71px;
	}
	.right {
		width: 540px;
		display: flex;
		flex-direction: column;
		gap: 16px;
	}
	.r1,
	.r2,
	.r3 {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
		width: 445px;
		height: 56px;
		gap: 32.45px;
		background-color: #f7f2f7;
		border-radius: 8px;
	}
	.r2 {
		margin-left: 48px;
	}
	.r3 {
		margin-left: 95px;
	}
	.star-row {
		display: flex;
		flex-direction: row;
		gap: 8.45px;
	}
	.r-text {
		font-size: 17px;
		font-weight: bold;
		color: #512051;
	}
	.row2 {
		width: 1110px;
		height: 266px;
		display: flex;
		flex-direction: row;
		gap: 30px;
	}
	.col1,
	.col2,
	.col3 {
		width: 350px;
		height: 234px;
		background-color: #512051;
		padding: 40px 32px 0 32px;
		border-radius: 8px;
	}
	.col2 {
		margin-top: 16px;
	}
	.col3 {
		margin-top: 32px;
	}
	.bottom-abso {
		position: absolute;
		bottom: 0;
		right: 0;
	}
	.bottom-abso-alt {
		display: none;
	}
	.profile {
		display: flex;
		flex-direction: row;
		gap: 23px;
		margin-bottom: 31px;
	}
	.name {
		font-size: 17px;
		color: white;
		font-weight: bold;
	}
	.status {
		font-size: 17px;
		color: #ee69a4;
	}
	.pro-img {
		width: 40px;
		height: 40px;
		object-fit: cover;
		border-radius: 100%;
	}
	.col {
		display: flex;
		flex-direction: column;
		gap: 4px;
	}
	.pro-text {
		font-size: 17px;
		color: white;
		font-weight: 500;
		line-height: 22px;
		letter-spacing: -0.3px;
	}
	@media only screen and (max-width: 375px) {
		.top-abso {
			display: none;
		}
		.top-abso-alt {
			position: absolute;
			top: 0;
			left: 0;
		}
		.container {
			margin-top: 82px;
			display: flex;
			flex-direction: column;
		}
		.row1 {
			width: 327px;
			display: flex;
			flex-direction: column;
			align-items: center;
			justify-content: initial;
		}
		.left {
			text-align: center;
		}
		.heading {
			width: 327px;
			font-size: 40px;
			line-height: 32px;
			letter-spacing: -1.43px;
			margin-bottom: 17px;
			color: #512051;
		}
		.text {
			width: 327px;
			margin-bottom: 39px;
		}
		.right {
			width: 327px;
			flex-direction: column;
			gap: 16px;
		}
		.r1,
		.r2,
		.r3 {
			flex-direction: column;
			width: 327px;
			height: 78px;
			gap: 15.23px;
		}
		.r2 {
			margin-left: 0;
		}
		.r3 {
			margin-left: 0;
		}
		.star-row {
			display: flex;
			flex-direction: row;
			gap: 8.45px;
		}
		.row2 {
			margin-top: 49px;
			width: 327px;
			height: auto;
			display: flex;
			flex-direction: column;
			gap: 16px;
			margin-bottom: 99px;
		}
		.col1,
		.col2,
		.col3 {
			width: 327px;
			height: 248px;
			padding: 40px 32px 0 32px;
		}
		.col2 {
			margin-top: 0;
		}
		.col3 {
			margin-top: 0;
		}
		.bottom-abso {
			display: none; 
		}
		.bottom-abso-alt {
			position: absolute;
			bottom: 0;
			width: 1085px;
			height: 673px;
		}
	}
</style>
