# Tot
code totem

<style>
    #test1 {
        display: inline-block;
        position: absolute;
        margin-left: 0;
        margin-right: 20px;
    }

    #test2 {
        display: inline-block;
        margin-right: 15px;
    }

    #imgcontainer {
        margin-top: 38px;
        margin-left: 120px;
        margin-right: 20px;
        display: block;
    }
</style>
<script src="http://pierrecharles.net/victor/jquery.1.6.2.min.js" type="text/javascript"></script>
<script>
    var jquery_1_6_2;
    var $i;
    $i = jQuery_1_6_2 = jQuery.noConflict();
</script>
<script src="http://pierrecharles.net/victor/$i_jquery_1_6_2.imagemapster.js" type="text/javascript"></script>
<div id="imgcontainer">
    <div id="test1" style="position:relative; margin-bottom:20px;">
        <img id="backround1" src="http://pierrecharles.net/victor/images/backround1.png" alt="backround" usemap="#back1" width="600">
    </div>
    <div id="test2" style="position:relative">
        <img id="backround2" src="http://pierrecharles.net/victor/images/backround2.png" alt="backround2" usemap="#back2" width="600">
    </div>
    <!-- MAP1 -->
    <map name="back1">
        <area id="9" href="#" cases="area14" shape="rect" coords="258,567,290,649"/>
        <area id="14" href="#" cases="area14" shape="rect" coords="193,317,357,392"/>
        <area id="10" href="#" cases="area10" shape="rect" coords="874,479,907,559"/>
        <area id="11" href="#" cases="area11" shape="rect" coords="865,558,922,638"/>
        <area id="12" href="#" cases="area12" shape="rect" coords="836,639,948,718"/>
        <area id="13" href="#" cases="area13" shape="rect" coords="827,720,968,792"/>
        <area id="15" href="#" cases="area15" shape="rect" coords="807,323,971,395"/>
        <area href="#" cases="area15" shape="rect" coords="874,479,907,559"/>
        <area href="#" cases="area15" shape="rect" coords="865,558,922,638"/>
        <area href="#" cases="area15" shape="rect" coords="836,639,948,718"/>
        <area href="#" cases="area15" shape="rect" coords="827,720,968,792"/>
        <area href="#" cases="area10" shape="rect" coords="807,323,971,395"/>
        <area href="#" cases="area11" shape="rect" coords="807,323,971,395"/>
        <area href="#" cases="area12" shape="rect" coords="807,323,971,395"/>
        <area href="#" cases="area13" shape="rect" coords="807,323,971,395"/>
    </map>
    <!-- MAP2 -->
    <map name="back2">
        <area id="0" href="#" cases="area0" shape="rect" coords="243,558,302,640"/>
        <area id="1" href="#" cases="area1" shape="rect" coords="255,641,288,721"/>
        <area id="2" href="#" cases="area2" shape="rect" coords="220,723,333,795"/>
        <area id="3" href="#" cases="area3" shape="rect" coords="864,401,896,479"/>
        <area id="4" href="#" cases="area4" shape="rect" coords="858,480,917,561"/>
        <area id="5" href="#" cases="area5" shape="rect" coords="864,564,894,644"/>
        <area id="6" href="#" cases="area6" shape="rect" coords="820,720,962,798"/>
        <area id="7" href="#" cases="area7" shape="rect" coords="192,316,354,395"/>
        <area href="#" cases="area7" shape="rect" coords="243,558,302,640"/>
        <area href="#" cases="area7" shape="rect" coords="255,641,288,721"/>
        <area href="#" cases="area7" shape="rect" coords="220,723,333,795"/>
        <area href="#" cases="area0" shape="rect" coords="192,316,354,395"/>
        <area href="#" cases="area1" shape="rect" coords="192,316,354,395"/>
        <area href="#" cases="area2" shape="rect" coords="192,316,354,395"/>
        <area id="8" href="#" cases="area8" shape="rect" coords="804,319,965,394"/>
        <area href="#" cases="area8" shape="rect" coords="864,401,896,479"/>
        <area href="#" cases="area8" shape="rect" coords="858,480,917,561"/>
        <area href="#" cases="area8" shape="rect" coords="864,564,894,644"/>
        <area href="#" cases="area8" shape="rect" coords="820,720,962,798"/>
        <area href="#" cases="area3" shape="rect" coords="804,319,965,394"/>
        <area href="#" cases="area4" shape="rect" coords="804,319,965,394"/>
        <area href="#" cases="area5" shape="rect" coords="804,319,965,394"/>
        <area href="#" cases="area6" shape="rect" coords="804,319,965,394"/>
        <area id="9" href="#" cases="area9" shape="rect" coords="192,316,354,395"/>
    </map>
</div>
<!-- IMAGEJS -->
<script language="javascript">
    $i(document).ready(function () {
        //$i.noConflict();
        $i('#backround2').mapster({
            singleSelect: true,
            render_highlight: {
                altImage: 'http://pierrecharles.net/victor/images/coucheselection2.png'
            },
            mapKey: 'cases',
            fill: true,
            altImage: 'http://pierrecharles.net/victor/images/couchenoire2.png',
            fillOpacity: 1,
        });

        $i('#backround1').mapster({
            singleSelect: true,
            render_highlight: {
                altImage: 'http://pierrecharles.net/victor/images/coucheselection1.png'
            },
            mapKey: 'cases',
            fill: true,
            altImage: 'http://pierrecharles.net/victor/images/couchenoire1.png',
            fillOpacity: 1,
        });
    });
</script>
<!-- LES SONS-->
<audio id="totem4" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Totem4.mp3">
    <source src="http://pierrecharles.net/victor/sons/Totem4.ogg">
</audio>
<audio id="totem10" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Totem10.mp3">
    <source src="http://pierrecharles.net/victor/sons/Totem10.ogg">
</audio>
<audio id="totem6" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Totem6.mp3">
    <source src="http://pierrecharles.net/victor/sons/Totem6.ogg">
</audio>
<audio id="guitare1" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Guitare1.mp3">
    <source src="http://pierrecharles.net/victor/sons/Guitare1.ogg">
</audio>
<audio id="guitare2" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Guitare2.mp3">
    <source src="http://pierrecharles.net/victor/sons/Guitare2.ogg">
</audio>
<audio id="basse1" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Basse1.mp3">
    <source src="http://pierrecharles.net/victor/sons/Basse1.ogg">
</audio>
<audio id="basse2" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Basse2.mp3">
    <source src="http://pierrecharles.net/victor/sons/Basse2.ogg">
</audio>
<audio id="voices1" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Voices1.mp3">
    <source src="http://pierrecharles.net/victor/sons/Voices1.ogg">
</audio>
<audio id="voices4" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Voices4.mp3">
    <source src="http://pierrecharles.net/victor/sons/Voices4.ogg">
</audio>
<audio id="Drum4" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Drum4.mp3">
    <source src="http://pierrecharles.net/victor/sons/Drum4.ogg">
</audio>
<audio id="Drum5" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Drum5.mp3">
    <source src="http://pierrecharles.net/victor/sons/Drum5.ogg">
</audio>
<audio id="Mara1" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Mara1.mp3">
    <source src="http://pierrecharles.net/victor/sons/Mara1.ogg">
</audio>
<audio id="totem3" preload="auto">
    <source src="http://pierrecharles.net/victor/sons/Totem3.mp3">
    <source src="http://pierrecharles.net/victor/sons/Totem3.ogg">
</audio>
<script>
    //Totem3


    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#14').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Totem4


    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#15').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Totem6


    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function () {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#7').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    //Totem10


    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#8').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    //Case0 guitare2


    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#0').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case1 voices1


    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#1').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    //Case2 Drum4


    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#2').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case3 Mara


    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#3').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case4 Basse2


    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#4').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case5 guitare1


    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#5').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case6 Drum5


    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('voices1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('Mara1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('guitare1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('Drum4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('basse2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('totem6');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#6').click(function play() {
            var audio = document.getElementById('totem10');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case9 guitare


    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#9').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    //Case10 basse


    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#10').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    //Case11 guitare2


    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#11').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    //Case12 voices4


    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#12').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    //Case13 Drum5


    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('Drum5');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('totem3');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('basse1');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });


    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('guitare2');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });

    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('voices4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });



    $i(document).ready(function () {
        var playing = false;

        $i('#13').click(function play() {
            var audio = document.getElementById('totem4');
            if (audio.paused) {
                audio.pause();
            } else {
                audio.pause();
                audio.currentTime = 0
            }


        });
    });
</script>
