body{
    font-family: 'Open Sans',sans-serif;
    background-color: black;
}
#container{

    width: 1000px;
    height: 550px;
    background-color: rgb(18, 165, 153);
    margin: 20px auto;
    background-image: -o-repeating-linear-gradient(0,0,0,3);
}
#calculator{

    width: 280px;
    height: 520px;
    background-color: #101113;
    margin: 0 auto;
    top : 15px;
    position: relative;
    border-radius: 7px;
    box-shadow: rgb(12, 12, 12);
}
#result{

    height: 120px;
}
#history{
	text-align: left;
	height: 20px;
	margin: 0 20px;
	padding-top: 20px;
	font-size: 15px;
	color: #f3efef;
}
#output{
     text-align: right;
     height: 50px;
     margin: 0px 20px;
     font-size: 36px;
     background-color: rgb(253, 247, 247);
     color: rgb(12, 10, 10);
     border-radius: 7px;
}
#keyboard{

    height: 400px;
    padding-top: 20px;
}
.operator, .number, .empty{

    width: 40px;
    height: 40px;
    margin: 15px;
    float: left;
    border-radius: 50%;
    border-width: 0;
    font-weight: bold;
    font-size: 20px;
}
.number, .operator{
    cursor: pointer;
}
.operator:active, .number:active{
    font-size: 13px;
}
.operator:focus, .number:focus, .empty:focus{
    outline: 0;
}
button:nth-child(4){
    font-size: 20px;
    background-color: #80e496;
}
button:nth-child(8){
    font-size: 20px;
    background-color: #77f0e6;
}
button:nth-child(12){
    font-size: 25px;
    background-color: #faeb17e0;
}
button:nth-child(16){
    font-size: 20px;
    background-color: #a0c401;
}
button:nth-child(20){
    font-size: 20px;
    background-color: #0372f0;
    color: white;
}
