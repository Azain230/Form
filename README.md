<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Azain Institute</title>
  </head>
  <body
    style="
      font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande',
        'Lucida Sans', Arial, sans-serif;
      padding: 30;
    "
  >
    <div
      style="
        width: auto;
        padding: 25px;
        background-color: aliceblue;
      "
    >
      <fieldset style="padding: 20px">
        <legend>Information Desk</legend>

        <div style="margin:10px 0px ;">
          <label for="Username" style="display: block;" >Username</label>
          <input type="text" id="Username" placeholder="Enter Username" style="width: 250px;"/>
        </div>
       
        <div style="margin:10px 0px ;">
          <label for="First Name" style="display: block;" >First Name</label>
          <input type="text" id="First Name" placeholder="Enter First Name" style="width: 250px;" />
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="Last Name" style="display: block;" >Last Name</label>
          <input type="text" id="Last Name" placeholder="Enter Last Name" style="width: 250px;" />
        </div>

        <div style="margin: 10px 0px;">
        <label for="Dateofbirth" style="display: block;"> Date Of Birth </label>
        <input type="date" id="DateOfBirth" placeholder="Enter Date Of Birth" style="width: 250px;" >
        </div>

        <div style="margin: 10px 0px;">
        <label for="Email" style="display: block;"> Email </label>
        <input type="text" id="Email" placeholder="Enter Your Email" style="width: 250px;" >
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="Gender" style="display: block;" >Gender</label>
          <label for="Gender_male">
            <input type="Radio" value="1" name="Gender" id="Gender_male">
            Male
          </label>
          <label for="Gender_Female">
            <input type="radio" value="2" name="Gender" id="Gender_Female">
            Female
          </label>
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="First Name" style="display: block;" >Father's First Name</label>
          <input type="text" id="First Name" placeholder="Enter First Name" style="width: 250px;" />
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="Last Name" style="display: block;" >Father's Last Name</label>
          <input type="text" id="Last Name" placeholder="Enter Last Name" style="width: 250px;" />
        </div>

        <div style="margin:10px 0px ;">
          <label for="Last Name" style="display: block;" >CNIC number</label>
          <input type="text" id="Last Name" placeholder="Enter Father's CNIC Number" style="width: 250px;" />
        </div>

        <div style="margin: 10px 0px;">
        <label for="Email" style="display: block;"> Email </label>
        <input type="text" id="Email" placeholder="Enter Father's Email" style="width: 250px;" >
        </div>
                <div style="margin:10px 0px ;">
          <label for="First Name" style="display: block;" >Mother's First Name</label>
          <input type="text" id="First Name" placeholder="Enter First Name" style="width: 250px;" />
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="Last Name" style="display: block;" >Mother's Last Name</label>
          <input type="text" id="Last Name" placeholder="Enter Last Name" style="width: 250px;" />
        </div>
        
        <div style="margin:10px 0px ;">
          <label for="Last Name" style="display: block;" >CNIC number</label>
          <input type="text" id="Last Name" placeholder="Enter Mother's CNIC Number" style="width: 250px;" />
        </div>

        <div style="margin: 10px 0px;">
        <label for="Email" style="display: block;"> Email </label>
        <input type="text" id="Email" placeholder="Enter Mother's Email" style="width: 250px;" >
        </div>
        <hr>
        <div style="margin: 10px 0px;" >
            <input type="Submit" value="Submit">
        </div>
      </fieldset>
    </div>
  </body>
</html>
