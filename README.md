 [v0.0.9](https://github.com/littleflute/Stevie-Ray-Vaughan/edit/master/README.md)

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
        s += "01 Thunderbird.mp3";
    }
    else if(i==2)
    {
        s += "02 I'm Cryin'.mp3";
    }
    else if(i==3)
    {
        s += "03 You're Gonna Miss Me Baby.mp3";
    }
    else if(i==4)
    {
        s += "04 They Call Me Guitar Hurricane [Live].mp3";
    }
    else if(i==5)
    {
        s += "05 All Your Love (I Miss Loving) [Live].mp3";
    }
    else if(i==6)
    {
        s += "06 Come on, Pt. 3.mp3";
    }
    else if(i==7)
    {
        s += "07 Letter to My Girlfriend.mp3";
    }
    else if(i==8)
    {
        s += "08 Lenny.mp3";
    }
    else if(i==9)
    {
        s += "09 Don't Lose Your Cool [Live].mp3";
    }
    else if(i==12)
    {
        s += "12 Texas Flood [Live].mp3";
    }
    else if(i==14)
    {
        s += "14 Pride and Joy.mp3";
    }
    else if(i==16)
    {
        s += "16 Hug You, Squeeze You [Live].mp3";
    }
    else if(i==17)
    {
        s += "17 Don't Stop by the Creek, Son.mp3";
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






