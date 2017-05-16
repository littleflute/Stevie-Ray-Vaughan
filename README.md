 [v0.0.4](https://github.com/littleflute/Stevie-Ray-Vaughan/edit/master/README.md)

[SRV Disc 1](SRV Disc 1/)

<audio controls id="player"> 
  <source src="https://littleflute.github.io/Stevie-Ray-Vaughan/SRV Disc 1/18 Ask Me No Questions.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
html += " ABBA<br>ABBA gold<br>CD:<br>";
for(var n=1; n<=19; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/Stevie-Ray-Vaughan/SRV Disc 1/";
    if(i==1)
    {
        s += "01 Thunderbird [#].mp3";
    }
    else if(i==2)
    {
        s += "02 I'm Cryin' [#].mp3";
    }
    else if(i==18)
    {
        s += "18 Ask Me No Questions.mp3";
    }
    else
    {
        if(i<10) 
        {
    	    s += "0";
        } 
        s += i;
        s += "_曲目 ";
        s += i;
        s += ".mp3";
    }
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>






