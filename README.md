<style>
* {vertical-align:middle}
</style>
<script>
var boy = 0
var t = 0
var liked = "no"
var vrv = 0
</script>
<script>
var j = "<a id="username" href="javascript:void(0)" ></a> "
document.getElementById("yoda").innerHTML = j
</script>
<img src="https://crunchbase-production-res.cloudinary.com/image/upload/c_limit,h_600,w_600/v1422480063/h0fvargheeyaybm4oyyt.jpg" style="width:60px;height:20px;" id="picerer" />
<a><span id="name">Buddy Bud Bud</span></a>
<HR>
<img src="https://crunchbase-production-res.cloudinary.com/image/upload/c_limit,h_600,w_600/v1422480063/h0fvargheeyaybm4oyyt.jpg" style="width:300px;height:100px;">
<HR>
<p>kdjsflaskjdfoaisdfp</p><HR>
<input type="button" value="Add a comment" onclick="comment()" id="joe"> 
<input type ="button" value = "Like" onclick="like()">
<p id="printit"></p>
<span id="printiter"></span>
<div>
    <div class="div1" id="div">
    <a id="user" href="#"></a><span id="commenter"></span></div>
    <div class="div2"><p><i id="time"></i></p></div>
    
</div>
<style>
 
.div1 {
    float: left
}
 
.div2 {
float: right;
} 
</style>
 

<script>
function comment(){
var p = document.getElementById("commenter").value
if (vrv == 0)
{

if (p == undefined){
 
var inp = document.createElement("input");
var j = document.createElement("P")


inp.onkeydown = commenter.onkeydown;
        j.appendChild(inp)  

        document.getElementById("commenter").appendChild(j);
       
        inp.focus();
        inp.placeholder = "Write your comment here"
        inp.id="comment"
        inp.size="100"
 document.getElementById("commenter").onkeypress = function(){handle()}
vrv = 1
       }}
else{
inp.focus();
}
}
</script>
<script>
 var math = document.getElementById("commenter");
math.onkeydown = function(e) {
    if(e.keyCode === 13 || e.which === 13) {
/* YUI is the name of the person */
var yui = document.getElementById("name").innerHTML;
 
/* IDK what any of these are */
var w = document.getElementById("time");
var zxc = document.createElement("P");
var asd= document.createTextNode(": " + this.value);
var sdf = document.createTextNode(yui + ": " + this.value);
var pic = document.getElementById("picerer").src
var picture = document.createElement("img")
picture.src = pic
picture.style="width:60px;height:20px;" 
 
/* User is the user */
var user = document.createElement("a");
user.setAttribute("href", "#");
user.innerHTML = yui;
if (t == 0)
{ 
var cmter = document.getElementById("commenter");
cmter.appendChild(picture)
cmter.appendChild(user);
cmter.appendChild(document.createTextNode(": " + this.value));

this.style.display = 'none'
this.blur() 
var now = new Date();
var hour = now.getHours()

if (hour >= 12)
{
var bas = "pm"
}
else
{
var bas = "am"
}
var hours = now.getHours() % 12 || 12;
var minutes = now.getMinutes()
if (minutes < 10)
{
minutes = "0" + minutes
}
var timej = hours + ":" + minutes + " " + bas
var u = document.createTextNode(timej)
zxc.appendChild(u)
document.getElementById("time").appendChild(zxc)
vrv = 0
t = 1
}
else
{
 
t = 0
}}}
 
</script>
<script>
function like()
{
if (liked == "Yes")
{
boy -= 1
liked = "no"
}
else if (liked == "no"){
liked = "Yes"
boy += 1
}
 
var y = boy.toString()
if (boy != 1&&boy != 0)
{
document.getElementById("printit").innerHTML = "Likes: " + y
}
else if (boy == 1||boy == 0)
{
document.getElementById("printit").innerHTML = "Like: " + y
}
}
</script> 
    
