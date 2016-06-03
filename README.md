# travel
<html>
	<head>
		<script src="file:///C:\Users\gurusangamaprasad.S\Documents\jquery-1.12.4.js"></script>
		<script>
			$(document).ready(function(){
			$('#imply :checkbox').click(function() {
			var $this = $(this);
      
			if ($this.is(':checked')) {
			$(".tbh").css("visibility","visible");
			} else {
        
			}
			})
			$("#sub").click(function(){
			$(".tbv").slideUp("slow");
			$("#shown").css("visibility","visible");
			})
			$("#gb").click(function(){
			$(".tbv").show();
			$("#shown").css("visibility","hidden");
			})
			});
			
		</script>
		<style>
		.Wrapper
		{
		max-width:1000px;
		}
		
		header
		{
		text-align:center;
		padding:15px;
		-webkit-box-shadow: 2px 5px 5px 0px rgba(230, 205, 230, 1);
		margin-bottom:20px;
		background-color:#1C2833;
		-webkit-border-radius:10px;
		
		width:100%;
		}
		.tbv
		{
		
		}
			h1,h3
			{
				font-family:Tahoma;
			}
			.tbh
			{
			visibility:hidden;
			}
			body
			{
			font-family:Arial;
			color:white;
			background:-webkit-linear-gradient(-180deg,#34495E,#212F3C);
			}
			input
			{
				-webkit-border-radius:10px;
			}
			input[type="button"],input[type="submit"]
			{
			background-color:black;
			color:white;
			-webkit-box-shadow: 2px 5px 5px 0px rgba(230, 205, 230, 1);
			}
			input[type="submit"]
			{
			 padding:10px;
			 margin-left:45%;
			}
			input[type="file"]
			{
			width: 0.1px;
	        height: 0.1px;
	        opacity: 0;
			overflow: hidden;
			position: absolute;
			z-index: -1;
			}
			input[type="file"] + label {
			
			font-weight: 700;
			color: white;
			background-color: black;
			display: inline-block;
			padding:3px;
			border:1px solid black;
			}

			input[type="file"]:focus + label,
			input[type="file"] + label:hover {
			background-color: ;
			}
			input[type="file"] + label {
			cursor: pointer; /* "hand" cursor */
			}
			input[type="file"] + label 
			{
			margin-right:5%;
			margin-left:3%;
			-webkit-border-radius:10px;
			-webkit-box-shadow: 2px 5px 5px 0px rgba(230, 205, 230, 1);
			}
			input[type="file"]+ label * {
			outline: 1px dotted #000;
			outline: -webkit-focus-ring-color auto 5px;
			-webkit-box-shadow: 2px 5px 5px 0px rgba(230, 205, 230, 1);
			margin-right:5%;
			pointer-events: none;
		}
		input[type="checkbox"] {
    display
}
input[type="checkbox"] + label {
    display:inline-block;
    width:19px;
    height:19px;
	margin:-1px 4px 0 0;
    background-image:url("http://www.clipartbest.com/cliparts/yTo/gj4/yTogj4zEc.png") ;
	cursor:pointer;
	}
	input[type="checkbox"]:checked + label {
    background:url("http://www.clker.com/cliparts/t/F/v/y/g/I/nxt-checkbox-checked-md.png") -19px top no-repeat;
}
#shown{
visibility:hidden;
}

		</style>
	</head>
	<body>
		<div id="Wrapper">
			<header>
			<h1>SPAIN CHECKLIST</h1>
			</header>
			<div id="shown">
				<h3>Your application will be submitted <h3>
				<input type="button" value="Go Back" id="gb"/>
			</div>
			<div class="tbv">
				Intended date of travel to the Schengen territory:<input type="date" required/></br></br>
				<form action="" id="imply">
				<input type="checkbox" />Between your date of application and date of travel to Spain, do you intend to travel to any other country</br>
				</form>
				<form action="">
				<div class="tbh">
				Date of travel: <input type="date" class="tbh"/></br></br>
				Name of the Country: <input type="text" class="tbh"/></br></br>
				<input type="checkbox" />Have you been informed by the VFS staff about the stipulated processing time?</br>
				</form>
				<form id="form11">
				<input type="checkbox" />Do you wish to continue with your application inspite of the stipulated processing time?</br>
				</div>
			</form>
			
			<h1>Minimum documentation for all visas categories:</h1>
			<form>
			<h3>Passport</h3>
			 <input type="checkbox" id="c1"/><label for="c1"></label>Valid at least 3 months beyond the stay in Spain with two blank pages</br>
			 <input type="checkbox" id="c1"/><label for="c1"></label>Not older 10 years when applying for a visa </br>
			 <input type="checkbox" id="c1"/><label for="c1"></label>With at least 2 blank pages </br>
			 <input type="checkbox" id="c1"/><label for="c1"></label>Photocopies of all the pages of the current and previous passport (if any). <input type="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>

			 <h3>Photographs</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Not more than 6 months old</br>
<input type="checkbox" id="c1"/><label for="c1"></label>With white background.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Size: 4.5cmx3.5 cm<input type="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Visa application form for Schengen Visa</h3>
<input type="checkbox" id="c1"id="c1"/><label for="c1"></label>Either filled in Blue pen or printed online.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Must bear original signatures of the applicant on page 3 (field no. 37) and page 4.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Two photocopies of the duly filled application form. <input type="file" id="file" multiple/><label for="file">Choose a file</label><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Covering letter from the applicant</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Purpose of travel</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Dates of travel. &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp<input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Travel Insurance Policy</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Issued by insurance company as per the EU guidelines.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Valid for at least 15 days from the date of return to India.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Minimum coverage of 30,000 Euros or 50,000 $</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Sworn declaration for travel insurance signed by the applicant. <input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Travel itineraries</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Hotel accommodation.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Confirmed return flight tickets.<input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Proof of economic means</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Salary slips for last six months.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Personal bank statement for the last three months (either stamped on first/last page or original bank statement).</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Income tax returns for last three years.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Copy of PAN card of the applicant (if available).<input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Authorization letter in favour of VFS Global.</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Signed by the applicant.<input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>For business visas</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Invitation letter from the Spanish company.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Support letter from the Indian company.<input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>

<h3>For minor applicants</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Application form signed by both the parents</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Passport copy of parents in case of minor applicants.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>NOC from parents in case the minor applicant is travelling with one parent or legal guardian.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Financial documents of parents must be accompanied by photocopy of the parents’
passports. <input type="file" id="file" multiple/><label for="file">Choose a file</label><input type="button" value="Upload"/> <input type="button" value="Delete file"></br></br></br>
<h3>Documents for family Visit</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Original Invitation before Policia Nacional in case of family or friend visit. (1 photocopy)</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Attested copy of the passport and the DNI or residence card of the person living in Spain. <input type="file" id="file" multiple/><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Documents for Students</h3>
<input type="checkbox" id="c1"/><label for="c1"></label>Invitation Letter from Spanish University /Institute- Admission Confirmation Letter.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Transactions of the fee payment.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Proof of sufficient economic means. Financial documents of parents must be accompanied</br>
by photocopy of the parent’s passports and a letter of responsibility. <input type="file" id="file" multiple/><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
<h3>Documents for Seaman</h3>
<input type="checkbox" id="c1" /><label for="c1"></label>Original letter from the local shipping agents</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Original letter from the shipping agents in Spain.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Continuous discharge book and photocopy of the same.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>Flight reservations.</br>
<input type="checkbox" id="c1"/><label for="c1"></label>“Anejo II: Impreso para marinos en Transito sujetos a la obligación de visados” issued by “El
puesto fronterizo del puerto” duly filled and stamped by the competent authorities. &nbsp  &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp &nbsp<input type="file" multiple/><input type="button" value="Upload"/> <input type="button" value="Delete file"/></br></br></br>
			</form>
			<p>Note: The above is not an exhaustive list of documentation. Applicant can be requested to
submit additional documents or may be called for an Interview (if required) by the Embassy. The
visa fee, according to Schengen regulations, is non-refundable. All original documents must
always be accompanied by at least one photocopy of the same.</p>
        <form>Declaration:
I <input type="text" placeholder="Name">..Passport <input type="text" placeholder="passpost number">voluntarily agrees to avail the services of
VFS Global Services Pvt. Ltd. to apply for a Schengen
Visa at the Spain Desk.
</form>
		
		<p>Note:Upload all the documents in the respective section</p>
		<input type="submit" value="SUBMIT" id="sub"/>
		</div>
		</div>
	</body>
</html>
