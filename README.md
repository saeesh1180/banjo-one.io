# banjo-one.io
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
	<style> 
		#get-started .form-control, #get-started .form-select {
    border-radius: 0;
    color: #30003C;
    font-size: calc(0.7em + 1vw);
    padding: 1em 0.8em;
}
.form-control {
    display: block;
    width: 100%;
    padding: 0.375rem 0.75rem;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    border-radius: 0.25rem;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}
#get-started .form-select {
    color: #939393;
}
#get-started .form-control, #get-started .form-select {
    border-radius: 0;
    color: #939393;
    font-size: calc(0.7em + 1vw);
    padding: 1em 0.8em;
}
.form-select {
    display: block;
    width: 100%;
    padding: 0.375rem 2.25rem 0.375rem 0.75rem;
    -moz-padding-start: calc(0.75rem - 3px);
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    background-color: #fff;
   /* background-image: url(data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23343a40' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M2 5l6 6 6-6'/%3e%3c/svg%3e);*/
    background-repeat: no-repeat;
    background-position: right 0.75rem center;
    background-size: 16px 12px;
    border: 1px solid #ced4da;
    border-radius: 0.25rem;
    transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
}
#get-started .tiny-disc {
    color: #9C9C9C;
    text-decoration: none;
}
small {
    font-size: 0.775em;
    line-height: 1.4;
    color: #0E0E0E;
}
#get-started .tiny-disc a {
    color: #9C9C9C;
    font-weight: 700;
    text-decoration: none;
}
#get-started .mainBtn {
    max-width: 100%;
    width: 100%;
}
.mainBtn {
    background: #0039F6;
    padding: 20px 15px;
    font-weight: 800;
    max-width: 588px;
    font-weight: 700;
    font-size: calc(0.88em + 0.7vw);
}
	</style>
</head>
<body>
	<section id="get-started">
		<div class="container">
	<div class="row justify-content-center">
					<div class="col-12 col-md-6">
						<form action="http://www2.banjoloans.com/l/965093/2022-04-16/2711d" method="post" class="">
							<div class="row mb-3">
								<div class="col-12">
									<input type="text" name="first_name" class="form-control" placeholder="First Name">
								</div>
							</div>
							<div class="row mb-3">
								<div class="col-12">
									<input type="phone" name="phone" class="form-control" placeholder="Phone Number">
								</div>
							</div>
							<div class="row mb-3">
								<div class="col-12">
									<input type="email" name="email" class="form-control" placeholder="Email Address">
								</div>
							</div>
							<div class="row mb-3">
								<div class="col-12">
									<select class="form-select" id="business_age" name="business_age">
										<option selected="" disabled="">Have You Been In Business Over 2 Years?</option>
										<option value="YES">Yes</option>
										<option value="NO">No</option>
										<option value="UNSURE">Unsure</option>
									</select>
								</div>
							</div>
							<div class="row mb-3">
								<div class="col-12">
									<select class="form-select" id="business_revenue" name="business_revenue">
										<option selected="" disabled="">Does Your Business Make $500k p.a?</option>
										<option value="YES">Yes</option>
										<option value="NO">No</option>
										<option value="UNSURE">Unsure</option>
									</select>
								</div>
							</div>
							<small class="tiny-disc">By registering and using this site, you are agreeing to the <a href="javascript:;">Terms &amp; Conditions</a> &amp; <a href="javascript:;">Privacy Policy</a>.</small>
							<button type="submit" class="btn d-block mx-auto my-2 my-md-4 mainBtn rounded-pill text-white align-items-center justify-content-center" id="calculate">Get started</button>
							<img src="img/norton.jpg" class="img-fluid mx-auto d-block" alt="">
								<!-- on submit remove the form and display a thank you message -->
							<div class="form-group d-none success-msg mb-5">
								<p class="text-center">Thank you! We will contact you shortly.</p>
							</div>
						</form>
					</div>
				</div>
			</div>
				</section>
</body>
</html>
