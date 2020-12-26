document.getElementById("ttNumber").onchange=function(){
document.getElementsByClassName("btn-primary")[0].click()
setTimeout(function() {
 document.getElementsByClassName("checkbox")[1].click()
document.getElementsByClassName("btn-primary")[6].click()
document.getElementsByClassName("checkbox")[4].click()
}, 500);
setTimeout(function() {
document.getElementsByClassName("checkbox")[6].click()
document.getElementsByClassName("btn-primary")[8].click()
document.getElementsByClassName("btn-primary")[9].click()
document.getElementById("ttNumber").value=''
}, 1000);
}