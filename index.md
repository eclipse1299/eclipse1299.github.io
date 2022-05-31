<html>
    <head>
        
    </head>
    <body> <p> 
<canvas id = "canvas1" onmousemove="coord(event)"> </canvas>
<style>
#canvas1
{
position: absolute;
top:50%;
left:50%;
transform: translate(-50%, -50%);
border: 5px solid white;

}
#demo
{
position: absolute;
top:116%;
left:50%;
transform: translate(-50%, -50%);
border: 5px solid white;
    color: black

}
#credit
{
position: absolute;
top:95%;
left:50%;
transform: translate(-50%, -50%);
border: 5px solid black;
background-color: cyan
  cursor: pointer
    color : black

}

#cream, #lamp, #cream2,#bg,#arrow_left,#jump_pic,#sun,#moon,#sun2,#roll_pic,#arrow_right, #run, #jump, #bg2,#button2, #basics,#rock1,#bar, #rock2, #roll,#roll2,#barBorder,#blueBar, #dead, #tree, #wings, #wings2, #bubble,#bubble2,#ice,#pause,#juice,#demo,#cool,#bush,#bird_icon,#energy_icon,#frost_icon,#bubble_icon,#run2,#jump2,#dead2,#button{
display:none
}
</style>
 <img id = 'cream2' src =  "https://i.imgur.com/PGFzsOP.png" alt = "ded">
 <img id = 'cream' src =  "https://i.imgur.com/rwpltI2.png" alt = "ded"> <img id = 'bg' src =  "https://i.imgur.com/uUWkWcg.png" alt = "ded">
          <img id = 'lamp' src =  " https://i.imgur.com/bSqWfDP.png" alt = "ded">
<img id = 'sun' src =  " https://i.imgur.com/jFQyeIJ.png" alt = "ded">
<img id = 'sun2' src =  "https://i.imgur.com/pPLC570.png " alt = "ded">
 <img id = 'jump_pic' src =  " https://i.imgur.com/EVFNqSh.jpg" alt = "ded">

<img id = 'arrow_left' src =     "https://i.imgur.com/fogzEsc.png" alt = "ded">
<img id = 'arrow_right' src =     "https://i.imgur.com/8ChbbcY.png" alt = "ded">
<img id = 'basics' src =  " https://i.imgur.com/omhhgYA.png" alt = "ded">
<img id = 'juice' src =  "https://i.imgur.com/2ibgsro.png" alt = "ded">
              <img id = 'button2' src =  "https://i.imgur.com/cgyvexY.png" alt = "ded">
 <img id = 'button' src =  "https://i.imgur.com/wUwjeDg.png" alt = "ded">
             <img id = 'run' src =  "https://i.imgur.com/E9vjUqw.png" alt = "ded" >
             <img id = 'run2' src =  "https://i.imgur.com/uURk4Hs.png" alt = "ded" >
       <img id = 'jump' src =  "https://i.imgur.com/SmykFho.png" alt = "ded">
        <img id = 'bar' src =  "https://i.imgur.com/wcpEFDC.png" alt = "ded">
       <img id = 'jump2' src =  "https://i.imgur.com/p3Hl2JI.png" alt = "ded" >
  <img id = 'moon' src =  "https://i.imgur.com/LEQrMNq.png" alt = "ded" >
          <img id = 'bg2' src =  "https://img.itch.zone/aW1hZ2UvMTIxNjU4LzU2MDQxMC5wbmc=/original/hCUwLQ.png" alt = "ded">
            <img id = 'rock1' src =  "https://i.imgur.com/D0Dx5Gj.png" alt = "ded">
              <img id = 'rock2' src =  "https://i.imgur.com/qR0Pqfr.png" alt = "ded" >
  <img id = 'roll' src =  "https://i.imgur.com/NibDVko.png" alt = "ded">
  <img id = 'roll2' src =  "https://i.imgur.com/uEMjonn.png" alt = "ded">
   <img id = 'dead' src =  "https://i.imgur.com/wmXgcFp.png" alt = "ded">
   <img id = 'dead2' src =  "https://i.imgur.com/kPLhquT.png" alt = "ded">
   <img id = 'tree' src =  "https://i.imgur.com/gSnubRb.png" alt = "ded">
<img id = 'pause' src =  "https://i.imgur.com/l1plXsX.png" alt = "ded">

<img id = 'wings' src =     "https://i.imgur.com/6c9zfZw.png" alt = "ded">
<img id = 'wings2' src =     "https://i.imgur.com/LRS2Y37.png" alt = "ded"><img id = 'barBorder' src =     "https://i.imgur.com/KDtlWac.png" alt = "ded">
<img id = 'blueBar' src =     "https://i.imgur.com/bSGXz46.png" alt = "ded">

<img id = 'bubble2' src =     "https://i.imgur.com/LB1Zyjv.png" alt = "ded">
<img id = 'bubble' src =     "https://i.imgur.com/x7BJpd0.png" alt = "ded">
<img id = 'ice' src =     "https://i.imgur.com/LPs7QM0.png" alt = "ded">
<img id = 'cool' src =     "https://i.imgur.com/qD9fnNY.png" alt = "ded">
<img id = 'bush' src =     "https://i.imgur.com/ky4F5Wk.png" alt = "ded">
<img id = 'frost_icon' src =     "https://i.imgur.com/9CpnbFU.png" alt = "ded">
<img id = 'energy_icon' src =     "https://i.imgur.com/G9WRRJF.png" alt = "ded">
<img id = 'bird_icon' src =     "https://i.imgur.com/dIFOyYt.png" alt = "ded">
<img id = 'bubble_icon' src =     "https://i.imgur.com/fNXIYoH.png" alt = "ded">
<img id = 'roll_pic' src =  " https://i.imgur.com/GB1Mkiy.jpg" alt = "ded">
<audio id = 'collectsound' src = 'https://opengameart.org/sites/default/files/magical_1_0.ogg'> 
<audio id = 'collectsound2' src = 'https://opengameart.org/sites/default/files/magical_2.ogg'> 
<audio id = 'collectsound3' src = 'https://opengameart.org/sites/default/files/magical_4.ogg'> 
<audio id = 'footstep' src = 'https://sndup.net/pgwc/d'> 
<audio id = 'footstep1' src = 'https://archive.org/download/qubodupImpactStone/step_cloth1.ogg'> 
<audio id = 'footstep3' src = 'https://archive.org/download/qubodupImpactStone/step_cloth3.ogg'> 
<audio id = 'footstep4' src = 'https://archive.org/download/qubodupImpactStone/step_cloth4.ogg'> 
<audio id = 'footstep2' src = 'https://archive.org/download/qubodupImpactStone/step_cloth2.ogg'> 
<audio id = 'collectionsound' src = 'https://opengameart.org/sites/default/files/coin.wav'> 
<audio id = 'click' src = 'https://opengameart.org/sites/default/files/Menu%20Selection%20Click.wav'> 
<audio id = 'click2' src = 'https://opengameart.org/sites/default/files/Metal%20Click.wav'> 
<audio id = 'landjump' src = 'https://opengameart.org/sites/default/files/jumpland.wav'> 
<audio id = 'jumpgrunt1' src = 'https://archive.org/download/qubodupImpactStone/jumppp11.ogg'> 
<audio id = 'jumpgrunt2' src = 'https://archive.org/download/qubodupImpactStone/jumppp22.ogg'>
<audio id = 'fall' src = 'https://opengameart.org/sites/default/files/fall.wav'> 
<audio id = 'hit1sound' src = 'https://archive.org/download/qubodupImpactStone/qubodupImpactStone.ogg'> 
<audio id = 'rollsound' src = 'https://opengameart.org/sites/default/files/sfx_jump.flac'> 
<audio id = 'bgmusic2' src = 'https://opengameart.org/sites/default/files/03%20track%203.flac'> 
<audio id = 'bgmusic' src = 'https://opengameart.org/sites/default/files/dj%20soul%20-%20Summer%20Adventure_0.mp3'> 
<audio id = 'pop' src = 'https://opengameart.org/sites/default/files/pop.ogg'> 
<audio id = 'flap' src = 'https://opengameart.org/sites/default/files/dragonflap.mp3'> 

 <script> 
var menu = true

const canvas = document.querySelector('canvas')
const c = canvas.getContext('2d') 
canvas.width = 1024
canvas.height = 576
var points = 0
c.fillRect(0,0, canvas.width, canvas.height)
let  gravity = 0.09
var time = 0
var deltatime = 0
var x2 = 0
    var y2 = 0
    let basics_page1 = false, basics_page2 = false
var gentleman = true
var transition = false
let speed = 4
var cool = false
var night_mode = false
var ded = 2
var bubble = true
var pauseGame = false

let lastloop = 0
var just_unpaused = false
 var ground_level = 540
var player_hitbox =  {
    x : 70,
    y: ground_level-75 - 20,
    len : 40,
    hei: 75 + 20
}
    var bounds = canvas.getBoundingClientRect()
var ducking = false
var image_pause =  document.getElementById('pause')
var midair = false
let obstacles = []
let collect = []
var last_day = 0
var death = false
var superjump = false
let energized = false
let onpause = false
 var basic = false
var onbasic = false
function cred() {if(menu ==true || death == true){
  if(document.getElementById("demo").style.display == "block")
document.getElementById("demo").style.display = "none"
else
 document.getElementById("demo").style.display = "block";
}}
function collide(ob1,ob2) {
    if (ob1.x < ob2.x + ob2.len && ob1.x + ob1.len > ob2.x && ob1.y < ob2.y + ob2.hei && ob1.y + ob1.hei > ob2.y)
    return true
    else
     return false //f  x[0] < y[0] + y[2] and x[0] + x[2] > y[0] :
}
class control {
 constructor(){
     this.keys = [];
    
     window.addEventListener('keydown', x => { //note : lexical scoping is used as js forgot basically function(x) wont work
      this.pressedKey = x.key.toLowerCase()
       
         if ((this.pressedKey == "w" || 'a' || 'enter' || ' ' || 'shift') && this.keys.indexOf(this.pressedKey) === -1){
     this.keys.push(this.pressedKey)
 }
//if(event.keyCode == 32 && event.target == document.body) {
//    event.preventDefault();
 // }

   
     })
       window.addEventListener('keyup', x => { //note : lexical scoping is used as js forgot basically function(x) wont work
         if (this.pressedKey == "w" || 'a' || 'enter' || ' ' || 'shift'){
     this.keys.splice(this.keys.indexOf(this.pressedKey) ,1)
    
         }

     })
     window.addEventListener('click', function(event){
    // Capture the Window X & Y coordinates of the mouse cursor
     bounds = canvas.getBoundingClientRect() // to get the coordinates according to the canvas not window
    var x = event.clientX - bounds.left
    var y = event.clientY - bounds.top
    if(x> 350-50 && x < 400 && y> 50 && y<150){
   gentleman = true
     click.play()
    }
   if(x> 600 && x < 700 && y> 50 && y<150){
    gentleman = false
       click.play()}
    if(x> canvas.width - 60 && x< canvas.width - 60 + 50 && y> 15 && y<= 65){
  bgmusic.pause()
    pauseGame = true
     click.currentTime = 0
              click.play()
    }
    if(x> canvas.width/2-55 && x< canvas.width/2-55+250 && y > canvas.height/2+ 47 && y < canvas.height/2+ 47 + 45 && menu){
    basic = true
    basics_page1 = true
    click.play()
    }
    //c.fillRect(canvas.width -70,canvas.height/2 - 30,45,85)
    //c.fillRect(30,canvas.height/2 - 30,45,85)
    if(basic){
    if(x> canvas.width-70 && x< canvas.width -70 + 45 && y > canvas.height/2 -30 && y < canvas.height/2 -30 +85){
        if(basics_page1){
            click.currentTime = 0
             click.play()
    basics_page2 = true
    basics_page1 = false}
         else if(basics_page2){
             click.currentTime = 0
              click.play()
    basic = false
    basics_page2 = false
    basics_page1 = false}
    }
    if(x> 30 && x< 30 + 45 && y > canvas.height/2 -30 && y < canvas.height/2 -30 +85){
        click.currentTime = 0
         click.play()
    basics_page2 = false
    basics_page1 = true
    }}
}, false)


 }   
    
}
const input = new control() 
function paused()
{

    if(input.keys.indexOf('enter') > -1 && !basic){
         if(pauseGame|| menu){
    click.play()
    pauseGame = false
    just_unpaused = true
    menu = false
document.getElementById("demo").style.display = "none"
         }
 if (ded<=0){

document.location.reload(true)
   }
   }
    if(input.keys.indexOf('escape') > -1){
    pauseGame = true
 bgmusic.pause()
click.play()
   }
   if(pauseGame)
   {c.font = '70px Serif'
    if(night_mode)
c.fillStyle = 'white'
   c.fillText( 'Press ENTER to resume', canvas.width/2-350, canvas.height/2)}
}
var ongentleman = 0
var count = 0, on_char = 0
function coord(e) {
  x2 = e.clientX - bounds.left;
   y2 = e.clientY- bounds.top;
  var coor = "Coordinates: (" + x2 + "," + y2 + ")"
  onpause = false
ongentleman = 0
onbasic = false
   if(x2> canvas.width - 60 && x2< canvas.width - 60 + 50 && y2> 15 && y2<= 65)
    onpause = true
    //350,100,50,
   if(x2> 350-50 && x2 < 400 && y2> 50 && y2<150)
   ongentleman = 1
   if(x2> 650-50 && x2 < 700 && y2> 50 && y2<150)
    ongentleman = 2
 if(x2> canvas.width/2-55 && x2< canvas.width/2-55+250 && y2 > canvas.height/2+ 47 && y2< canvas.height/2+ 47 + 45){
    onbasic = true
   }
}

class bg {
   
        constructor(){
             this.x = 0
             this.y = 0
             this.y2 = 0
        this.existence = true  
         this.image = document.getElementById('bg')
         this.image2 = document.getElementById('bg2')
         this.image3 = document.getElementById('bg')
         this.x2 = 0
         this.count = 0
         this.height = canvas.height
         this.height2 = canvas.height
   this.timer = 0
    this.sun = true
this.timer2 = 0
this.gre = 0
   
    }  
    draw(){
        
      c.drawImage(this.image3, this.x, this.y, canvas.width, this.height)
   
 c.drawImage(this.image, this.x + canvas.width - speed, this.y2, canvas.width, this.height2)
   if(night_mode ){
this.timer2 = 0
    this.timer+= deltatime
    if(this.timer>= 4500)
    this.sun = false
}if (this.sun)
c.drawImage(sun, this.gre, 15, 120,120)

  if(!night_mode ){
this.timer = 0
this.timer2 += deltatime
if(this.timer2>=4500)
this.sun = true}
       
    }
    update() {
   //   this.gre -= speed
     if(this.gre<=-100 && !night_mode)
   this.gre = canvas.width + 100
    this.draw()
     this.x -= speed  
    this.x2 -= speed
     if (this.x2 < 0 - canvas.width){
     this.x2 = 0 
      
     //this.y = 25
      }
     if (this.x < 0 - canvas.width){
         if (night_mode){
             this.count = 0
             count++
             this.height2 = 25 + canvas.height
             this.image =  document.getElementById('bg2')
            if (count ==2){
                  this.height = 25 + canvas.height
                  this.image3 = document.getElementById('bg2')}
                  }
                           if (!night_mode){
                               count = 0
             this.count++
             this.height2 = canvas.height
             this.image =  document.getElementById('bg')
            if (this.count ==2){
                  this.height = canvas.height
                  this.image3 = document.getElementById('bg')}
                  }
                   this.x = 0
    
    }}}
  const back = new bg()
  player_hitbox =  {
    x : 70,
    y: ground_level-75 - 20,
    len : 40,
    hei: 75 + 20
}   

let footinterval = 23
class Player {
    constructor(){
        this.position = player_hitbox
        this.vel = 3
        this.timer = 0
        this.jinterval = 1500
        this.dinterval = 680
        this.ground = ground_level
      this.footsound = 1
         this.position.y = this.ground-75 - 20
        this.acc = 16.5
        this.image = document.getElementById('run')
         this.image2 = document.getElementById('jump')
         this.image3 =  document.getElementById('dead')
          this.image4 =  document.getElementById('roll')
             this.barBorder =  document.getElementById('barBorder')
             this.blueBar =  document.getElementById('blueBar')
        
          this.image_wings = document.getElementById('wings2')
           this.image_bubble = document.getElementById('bubble')
           this.icon_frost = document.getElementById('frost_icon')
           this.icon_energy = document.getElementById('energy_icon')
           this.icon_bird = document.getElementById('bird_icon')
           this.icon_bubble = document.getElementById('bubble_icon')
           this.bar = document.getElementById('bar')
        this.anim = 0
        this.width = 96
        this.timer2 = 0
        this.cap = 4859
        this.once = true
        this.interval = 0
        this.up = true
        this.timer3 = 0

        this.jumpheight = 16.5
        this.timer4 = 0
        this.timer5 = 0
        this.timer_juice = 0
        this.bar_y = 80
        this.power_duration = 10000
        this.imageTextCool = document.getElementById('cool')
    }  
    powerup(){
        this.bar_y = 80
        if(superjump ){
        if(midair && this.timer3>= 50){
        flap.play()
}
         this.timer3+= deltatime
         c.drawImage(this.icon_bird, 10, this.bar_y-10, 40,40)
                       c.fillStyle = 'black'
        c.drawImage(this.bar,55,this.bar_y, 200 , 20)
        c.fillStyle = 'pink'
        c.fillRect(60, this.bar_y+5,190-( this.timer3/this.power_duration *190), 10)
          c.drawImage(this.barBorder,55,this.bar_y, 200 , 20)
        this.bar_y+= 40
        
        }
        if(this.timer3 >= this.power_duration)
        {
            this.timer3 = 0
            superjump = false
        
        }
        if(bubble){
         this.timer4+= deltatime
                          c.fillStyle = 'black'
                          c.drawImage(this.icon_bubble, 10, this.bar_y-10, 40,40)
         c.drawImage(this.bar,55,this.bar_y, 200 , 20)
        c.fillStyle = 'white'
        c.fillRect(60, this.bar_y+5,190-( this.timer4/this.power_duration *190), 10)
        c.drawImage(this.barBorder,55,this.bar_y, 200 , 20)
        this.bar_y+= 43
          }
        if(this.timer4 >= this.power_duration)
        {
            this.timer4 = 0
           bubble = false
           ded = 1
        
        }
    
         if(cool){
         this.timer5+= deltatime
                
                 c.fillStyle = 'black'
        c.drawImage(this.icon_frost, 10, this.bar_y-10, 40,40)
   
         c.drawImage(this.bar,55,this.bar_y, 200 , 20)
        
        
     
      c.drawImage(this.blueBar,60, this.bar_y+5,190-( this.timer5/this.power_duration *190), 10)
        c.drawImage(this.barBorder,55,this.bar_y, 200 , 20)
        this.bar_y+= 40
          if(this.timer5<= 800){
                    c.drawImage(this.imageTextCool, 300,canvas.height/2,  50/2 + 80,75/2 + 15 + 10+30)}
        }
        if(this.timer5 >= this.power_duration)
        {
            this.timer5 = 0
           cool = false
        }
        if(energized){
            this.power_duration = 15000
         this.timer_juice+= deltatime
                 c.fillStyle = 'black'
                 c.drawImage(this.icon_energy,10, this.bar_y-10,40,40)
         c.drawImage(this.bar,55,this.bar_y, 200 , 20)
        c.fillStyle = 'orange'
        c.fillRect(60, this.bar_y+5,190-( this.timer_juice/this.power_duration *190), 10)
        c.drawImage(this.barBorder,55,this.bar_y, 200 , 20)
        }
        else
        this.power_duration = 10000
        if(this.timer_juice >= this.power_duration)
        {
            this.timer_juice = 0
           energized = false
        }
    if (superjump ){
    this.jumpheight = 23.5
    gravity = 0.18
   
    }
    else{
    this.jumpheight = 16.5
    gravity = 0.09
    }
    if (bubble)
    ded = 2
    }
    draw(){
        if(!gentleman){
                     this.image = document.getElementById('run2')
         this.image2 = document.getElementById('jump2')
         this.image3 =  document.getElementById('dead2')
          this.image4 =  document.getElementById('roll2') 
          }
   
        this.position = player_hitbox
        c.fillStyle = 'blue'
        if(superjump && ded>0){
         if(ducking)
         c.drawImage(this.image_wings,0,0, 430, 610, 70- 50,  this.ground- 75 - 20 -110 + 60 , 105/2 , 75/2 + 15 + 10+60)
         else
        c.drawImage(this.image_wings,0,0, 430, 610, this.position.x- 50, this.position.y-110 + 60 , 105/2 , 75/2 + 15 + 10+60)
        }
          if(bubble){
         if(ducking)
         c.drawImage(this.image_bubble, 70- 40,  this.ground- 75 - 20 -80 + 60 , 105/2 + 70 , 75/2 + 15 + 10+60 + 15)
         else
        c.drawImage(this.image_bubble, this.position.x- 40, this.position.y-80 + 60 , 105/2 + 70 , 75/2 + 15 + 10+60 + 15)
        }
     //  c.fillRect(this.position.x, this.position.y, this.position.len , this.position.hei)
       if(!midair && ded >0 && !ducking){
     this.interval = 0
              this.width = 113
            if(this.footsound == 1)
              footstep1.play()
else if(this.footsound == footinterval + 1)

footstep2.play()
else if(this.footsound == footinterval * 2 + 1)
footstep3.play()
else if(this.footsound == footinterval * 3 + 1)
footstep4.play()
this.footsound++
if (this.footsound>= footinterval * 4 + 1)
this.footsound = 1
           this.cap = 4859
            if(!gentleman){
              this.width = 100
              this.cap = 4300}
        c.drawImage(this.image, this.anim,0 ,this.width, 170, this.position.x - 20, this.position.y, this.position.len + 30, this.position.hei)}
        if(midair  && ded >0){
            this.interval = 0
            this.width = 96
          this.cap = 2400
                     if(!gentleman){
              this.width = 83
              this.cap = 2075}
           c.drawImage(this.image2, this.anim,0 ,this.width, 170, this.position.x - 20, this.position.y, this.position.len + 30, this.position.hei)
        }
    
          if(ded <= 0){//animations for death
         bgmusic.loop = false
bgmusic.pause()
              if(ducking){
                        player_hitbox =  {
                                           x : 70,
                                            y: ground_level-75 - 20,
                                          len : 40,
                                         hei: 75 + 20
                                         }}// incase u were ducking when hit
            if(midair)
            player_hitbox.len = 40 //incase u were midair
              this.interval = 1
              if (this.once){ //anim needs start at zero or else the pics wont come properly 
                 this.anim = 0
                 this.once = false
                     }
                     hit1sound.volume = 0.5
                     if (this.anim == 0){
                        footstep1.pause()
                          footstep2.pause() 
 footstep3.pause() ; footstep4.pause()  ;collectionsound.pause() ;collectsound.pause();  collectsound2.pause();  collectsound3.pause()
                         
                     hit1sound.play()
                     }
            this.width = 234
            this.cap = 9824
                        if(!gentleman){
              this.width = 225.2
              this.cap = 9446}
        c.drawImage(this.image3, this.anim,0 ,this.width, 177, this.position.x - 85, this.position.y, this.position.len + 100, this.position.hei)
        if(this.anim>= this.cap - (17* this.width))
         fall.play()
         
        if (this.anim>= this.cap){
           
        death = true
        }
        }
        
        if(ducking && ded>0){ //if ur ducking
       
              this.interval = 4 //slower animation as we have less images for it
             this.width = 250
           this.cap = 1500
              if(!gentleman){
              this.width = 240
              this.cap = 1440}
              if(gentleman)
        c.drawImage(this.image4, this.anim,0 ,this.width, 170, this.position.x - 62, this.position.y - 62, this.position.len + 105, this.position.hei + 70)
        else
          c.drawImage(this.image4, this.anim,0 ,this.width, 170, this.position.x - 62, this.position.y - 62, this.position.len + 115, this.position.hei + 70)
           if (this.up){//the animation must start from the end of the sheet then reach the start and back to the end for the going down and coming up effect
                if (this.timer2>= this.interval){//this.timer to slow it down
                       this.timer2 = 0
                       this.anim -= this.width}
                       
                   else
                   this.timer2++}
        if (this.anim <= 0)
        this.up = false
          if (!this.up){
                if (this.timer2>= this.interval){
                       this.timer2 = 0
                       this.anim += this.width}
                       
                else
                this.timer2++}
        if (this.anim>= this.cap)
        this.up = true
        }
        
       if (this.timer2>= this.interval && !ducking){//for ducking a different block was made
        this.anim += this.width //to slow down the change of the images(for the animation)
        this.timer2 = 0}
        else 
        this.timer2++
      if (this.anim>= this.cap && ded>0 && !ducking)
      this.anim = 0
   
    }
    update(deltatime) {

     this.powerup()
      this.draw()
      this.position.y += this.vel
      if( this.position.y + this.position.hei + this.vel >= this.ground)
      this.vel = 0
      else 
         this.vel += gravity // acceleration
      if (input.keys.indexOf('shift') > -1 && !ducking && !midair && ded>0) {
          player_hitbox = {
    x : 70,
    y: this.ground - 75/2,
    len : 40,
    hei : 75/2
} 
rollsound.volume = 0.5
rollsound.currentTime = 0
rollsound.play()
this.anim = 1500 //cap for ducking
if(!gentleman)
this.anim =  1440
ducking = true
}
      if (input.keys.indexOf(' ') > -1 && !ducking && !midair && ded>0) {

          this.acc = this.jumpheight
   this.position.y -= this.acc
   this. acc--
   this.anim = 0
   this.position.len = 30
midair = true
jumpgrunt1.volume = 0.5
jumpgrunt2.volume = 0.5
if(Math.random()*2 > 1)
{jumpgrunt1.currentTime = 0
jumpgrunt1.play()}
else {
    jumpgrunt2.currentTime = 0
jumpgrunt2.play()}
}
if (this.acc < 0)
this.acc = 0
if(midair)
{this.position.y -= this.acc
   this. acc--}
  
if (Math.round(this.position.y + this.position.hei) >= this.ground && midair){
     this.position.len = 40
     if (ded>0)
    this.anim = 0
       landjump.volume = 0.5
    landjump.currentTime = 0
    landjump.play()
midair = false
this.acc = this.jumpheight
}

    if (ducking){
        if(this.timer> this.dinterval){
            if (ded>0)
            this.anim = 0
          this.timer = 0
          ducking = false
          player_hitbox =  {
                             x : 70,
                             y: this.ground- 75 - 20,
                             len : 40,
                                 hei: 75 + 20
                             }
        }
        else
        this.timer += deltatime
    }
    this.dinterval -= 0.001
    this.vel += 0.0001
    }
    menu()
    {    this.image_menu = document.getElementById('run2')
     c.drawImage(this.image,0,0,113,102.9 , 310,60, 80,80)
     if(ongentleman == 1)
     c.drawImage(this.image,0,0,113,170 , 310,60, 80,135)
   c.drawImage(this.image_menu, 0,0, 100,98 ,608,60, 80,80)
 if(ongentleman == 2)
        c.drawImage(this.image_menu, 0,0, 100,170 ,608,60, 80,140)

    }
}

const player = new Player()
function menuscreen()
{ let button = document.getElementById('button')
let button2 = document.getElementById('button2')
let basics = document.getElementById('basics') 
     if(menu && !basic)
   {c.font = '70px Serif'
   c.fillText( 'Press ENTER to start', canvas.width/2-320, canvas.height/2)
   
      c.drawImage(button, 300,50, 100,100)
   c.drawImage(button, 600,50, 100,100)
   if(gentleman) 
 c.drawImage(button2, 300,50, 100,100)
else
c.drawImage(button2, 600,50, 100,100)
   player.menu()
 c.font = '40px Serif'
 c.fillText( 'or learn the', canvas.width/2-250, canvas.height/2 + 80)

if(!onbasic )
 c.drawImage(basics, canvas.width/2-210,canvas.height/2)
else 
  c.drawImage(basics, canvas.width/2- 230,canvas.height/2 - 30, 600,150)


  }
if (basics_page1){
c.drawImage(arrow_right, canvas.width -70,canvas.height/2 - 30)
c.drawImage(jump_pic, 100, 70, 140,140)
c.font = '30px Serif'
c.fillStyle = ' white'
c.fillText('Press SPACE to jump over obstacles like bushes and rocks', 260, 150)
c.drawImage(roll_pic, 100, 240, 140,140)
c.fillText('Press SHIFT to roll under obstacles like trees and lamps', 260, 320)
c.fillText('The goal of the game is to collect as many ice creams as you can while', 100, 420)
c.fillText('surviving the longest.', 100, 460)
c.fillText('Your score is displayed on the top-left corner of the screen ', 100, 500)
c.fillText('and your time on the top-right corner', 100, 540)
}

if (basics_page2){
    c.font = '30px Serif'
c.fillStyle = ' white'

c.fillText('Powerups are rare items that make it easier to collect ice creams.' ,100,70 )
c.fillText('Their special effect usually lasts 10 seconds.' ,100,110 )
 c.font = '25px Serif'
c.fillText('Wings - Increase jumpheight', 210, 230)
c.fillText('Bubble - Protects against ', 710, 230)
c.fillText('any 1 obstacle ', 710, 260)
c.fillText('Ice stick - Doubles points gained ', 210, 430)
c.fillText('by ice creams ', 210, 460)
c.fillText('Juice - Increases powerup', 710, 430)
c.fillText('duration by 1.5x', 710, 460)
c.drawImage(wings2, 60, 150, 140,140)
c.drawImage(ice, 60, 350, 110,140)
let bub = document.getElementById('bubble')
c.drawImage(bub, 550, 150, 140,140)
c.drawImage(juice, 590, 350, 70,140)
c.drawImage(arrow_left, 30,canvas.height/2 - 30)
c.drawImage(arrow_right, canvas.width -70,canvas.height/2 - 30)
}

}

class obstacle  {
    constructor(bloc){
        this.position = bloc
         this.vel = 5
         this.image1 = document.getElementById('rock1')
         this.image2 = document.getElementById('rock2')
         this.image_bush = document.getElementById('bush')
         this.image_lamp = document.getElementById('lamp')
this.image = document.getElementById('tree')
    this.luck = Math.random() * 2
    this.once = true
    this.night = false
    if(night_mode)
    this.night = true
    this.ran = Math.floor( Math.random() * 3) * 1200 //the first part gives either 0,1 or 2 which decides which tree will come
    }  
    draw(){
        c.fillStyle = 'red'
         
         if (this.position.type == 2){
             
         if(!this.night)
         c.drawImage(this.image, this.ran,0,1200, 1500, this.position.x - 25 , this.position.y - 55 +30, this.position.len + 60, ground_level - this.position.y + 15 + 30)
         else
         c.drawImage(this.image_lamp,  this.position.x  , this.position.y +20, this.position.len + 15, ground_level - this.position.y -15  )
        // c.fillRect(this.position.x, this.position.y, this.position.len , this.position.hei)
         }
         else if(this.night){
          c.drawImage(this.image_bush, this.position.x - 13, this.position.y - 10 , this.position.len+ 35, this.position.hei + 25)
         // c.fillRect(this.position.x, this.position.y, this.position.len , this.position.hei)
          }
        else if (this.luck >= 1)
        c.drawImage(this.image1, this.position.x - 23, this.position.y - 10 , this.position.len+ 55, this.position.hei + 25)
        else
            c.drawImage(this.image2, this.position.x - 20, this.position.y - 10 , this.position.len+ 40, this.position.hei + 25)
         

    }
    update() {
        
      this.draw()
     this.position.x -= speed    
    if (collide(player_hitbox,this.position)){
        if(this.once){
        if(bubble)
            pop.play()
            bubble = false
      ded--
      this.once = false
    }
   }
 //    this.position.y += this.vel
 //    if( this.position.y + this.position.hei + this.vel >= canvas.height )
//      this.vel = 0
//   else 
 //       this.vel += gravity // acceleration
    }    
}
class collectible  {
    constructor(bloc){
        this.existence = true
        this.position = bloc
         this.vel = 5
         this.image = document.getElementById('cream')
        this.float = 1
         this.float2 = true
    }  
    draw(){
        if(this.existence === true){
        c.fillStyle = 'white'
      //  c.fillRect(this.position.x, this.position.y , this.position.len , this.position.hei)
      c.drawImage(this.image, this.position.x- 5, this.position.y-20 + 10 + this.float,this.position.len+5,this.position.hei+15)
     }
    }
    update() {
         if (this.float2)
      this.float += 0.2
      else 
      this.float -= 0.2
      if (this.float >= 5)
      this.float2 = false
      if (this.float <= -5)
      this.float2 = true
        if  (collide(player_hitbox,this.position) ){
            if (this.existence === true){

 collectionsound.volume = 0.3
 collectionsound.currentTime = 0
  collectionsound.play()

             points++
                if(cool)
                points++}
         this.existence = false
        
        }
         if (collide(this.position,obstacles[obstacles.length-1].position))
        this.position.y = ground_level - 75- this.position.hei - 20 // ground_level - 75 is y of obstacle - position.hei so that end of collectible touches the obstacle and -20 cuz it shud be easier to collect
         if(this.existence === true)
           this.draw()
     this.position.x -= speed    
     
    }}
 
 class powerups  {
    constructor(bloc){
        this.existence = true
        this.position = bloc
         this.vel = 5
         this.image = document.getElementById('wings2')
          this.image_bubble = document.getElementById('bubble')
          this.image_ice = document.getElementById('ice')
          this.image_juice =  document.getElementById('juice')
        this.float = 1
         this.float2 = true
         this.effect = false
         this.number = Math.floor(Math.random()* 4)
        this.sound = Math.floor(Math.random()*3)
         
    }  
    draw(){
        if(this.existence === true){
        c.fillStyle = 'orange'
    //   c.fillRect(this.position.x, this.position.y , this.position.len , this.position.hei)
       if (this.number == 1)
      c.drawImage(this.image, this.position.x- 20, this.position.y-110 + 60 + this.float, this.position.len + 50,this.position.hei+60)
      if (this.number == 0)
       c.drawImage(this.image_bubble, this.position.x- 20, this.position.y-100 + 60 + this.float, this.position.len + 50,this.position.hei+50)
         if (this.number == 2){
       c.drawImage(this.image_ice, this.position.x- 0, this.position.y-80 + 60 + this.float, this.position.len + 20,this.position.hei+30)

         }
               if (this.number == 3)
       c.drawImage(this.image_juice, this.position.x- 0, this.position.y-65 + 60 + this.float, this.position.len + 0,this.position.hei+32)
     }
    }
    update() {
         if (this.float2)
      this.float += 0.2
      else 
      this.float -= 0.2
      if (this.float >= 5)
      this.float2 = false
      if (this.float <= -5)
      this.float2 = true
      if  (collide(player_hitbox,this.position) ){
            if (this.existence === true){
             this.effect = true
collectsound.volume = 0.5
collectsound2.volume = 0.5
collectsound3.volume = 0.5
if(this.sound == 0)
 collectsound.play()
else if (this.sound == 1)
 collectsound2.play()
else
 collectsound3.play()
}
         this.existence = false
        
        }
      if (collide(this.position,obstacles[obstacles.length-1].position)&& obstacles[obstacles.length-1].position.type != 2 )
        this.position.y = ground_level - 75- this.position.hei - 20 // ground_level - 75 is y of obstacle - position.hei so that end of collectible touches the obstacle and -20 cuz it shud be easier to collect
     if(this.existence === true)
           this.draw()
     this.position.x -= speed 
     if (this.effect == true){
        if (this.number == 1 )   {
             this.effect = false
             superjump = true
             player.timer3 = 0
     
     }
        if (this.number == 0 )   {
             this.effect = false
             bubble = true
             player.timer4 = 0
     }
       if (this.number == 2 )   {
             this.effect = false
             cool = true
             player.timer5 = 0
     
     }
         if (this.number == 3 )   {
             this.effect = false
             energized = true
             player.timer_juice = 0
     
     }
     }
    }
    } 
let block = {
    x : 1100 + 10,
    y: ground_level - 75,
    len : 50 - 10,
    hei : 75,
    type: 1
} 
let wall = {
    x : 1100,
    y: 426 + 75/2 - 25 - 10,
    len : 50,
    hei : 85,
    type : 2
}

let min_interval = 1000, obtimer = 0, obinterval = Math.random() * 3500  + min_interval, collect_interval = Math.random() *3000 + 500
   obstacles.push(new obstacle({ //an object has to be in the obstacles array or it will  give an error in line 171 but if x of this obstacle is 1100 then 2 obstacles will be spawned and will be impossible to dodge also increasing obtimer to immediately give an obstacle will also result in 2 obstacles
    x : -100,
    y: 426 + 75/2 - 25 - 10,
    len : 50,
    hei : 85
}))
function ranobstacles(deltatime)
{
  if (obtimer > obinterval && !transition){
      
       if  ((Math.random() * 2) >= 1){
     obstacles.push(new obstacle( wall));
      obtimer = 0}
       else {
         obstacles.push(new obstacle(block));
           obtimer = 0
             }}
else
obtimer += deltatime
obstacles.forEach( obstacle => { if(ded>0)
obstacle.update() 
else
obstacle.draw() 
})
}
let collect_timer = 0, power = []
function rancollect(deltatime)
{
  if (collect_timer > collect_interval ){
       
     collect.push(new collectible({
    x : 1100,
    y: ground_level - 75/2 - 25,
    len : 50/2,
    hei : 75/2 + 15
} ));
collect_timer = 0
}
else
collect_timer += deltatime
collect.forEach( collectible => { if(ded>0)
collectible.update() 
else
collectible.draw() 
})
}
let power_timer = 0, power_interval = Math.random()* 2000 + 5000
function ranpower(deltatime)
{
  if (power_timer > power_interval && !transition){
       
     power.push(new powerups({
    x : 1100,
    y: ground_level - 75/2 - 25 - 30,
    len : 50/2 + 30,
    hei : 75/2 + 15 + 10
} ));
power_timer = 0
}
else
power_timer += deltatime
power.forEach( powerups => { if(ded>0)
powerups.update() 
else
powerups.draw() 
})
}
function text()
{   if(night_mode)
    c.fillStyle = 'white'
    else
    c.fillStyle = 'black'
    c.font = '40px Serif'
    c.fillText('Score: '+ points, 20,55)
 if(ded>0)
    time+= deltatime
    c.fillText( Math.round(time/10)/100, canvas.width - 100, 105)
    if(death){
c.font = '70px Serif'
    if(night_mode)
c.fillStyle = 'white'
   c.fillText( 'Press ENTER to restart', canvas.width/2-350, canvas.height/2)

}
}


function animate(timeStamp){

     c.fillStyle = 'black'
    c.fillRect(0,0,canvas.width,canvas.height)
   
         deltatime = timeStamp - lastloop

    lastloop = timeStamp
    if(just_unpaused || menu){
    deltatime = 0// as deltatime accumulates
    just_unpaused = false
    }
    
    if (pauseGame || menu && !basic)
    back.draw()
    if(menu )
    last_day = timeStamp
  
   paused()
   menuscreen()
   
      if (!death) 
    window.requestAnimationFrame(animate)
    
    if(!pauseGame && !menu){
         if(time- last_day>= 30000){
             speed+= 0.002
        transition = true
        if (time - last_day>= 36000){
            transition = false
        last_day = time
        if(night_mode)
        night_mode = false
        else{
           
        night_mode = true}
    }}
      if(night_mode)
 block = {
    x : 1100 +10,
    y: ground_level - 75 + 20,
    len : 70,
    hei : 55,
    type: 1
} 
else
 block = {
    x : 1100 + 10,
    y: ground_level - 75,
    len : 50 - 10,
    hei : 75,
    type: 1
}   
    if(ded>0)
    back.update()
        if(ded<=0)
    back.draw()
     
    obinterval = Math.random() * 3500  + min_interval
    collect_interval = Math.random() *3000 + 100
    power_interval = Math.random()* 2000 + 5000
    
    if(!onpause)
    c.drawImage(image_pause, canvas.width - 60, 15, 50,50)
    else 
     c.drawImage(image_pause, canvas.width - 70, 5, 70,70)
     
    if (min_interval > 200)
    min_interval -= 0.001
    if (obstacles.length > 20)
    obstacles.shift()
    if (collect.length > 30)
    collect.shift()
    if (power.length > 10)
    power.shift()
   
    
  
    player.update(deltatime)
    
    ranobstacles(deltatime)
    rancollect(deltatime)
    ranpower(deltatime)
    speed += 0.0002


 wall = {
    x : 1100,
    y: 426 + 75/2 - 25 - 10 -canvas.height + ground_level - 30,
    len : 50,
    hei : 85 + 30,
    type : 2
}
bgmusic.volume = 0.2
if(ded>0){

bgmusic.loop = true
bgmusic.play()
}
text()}
}
function afterdeath() {
       if(input.keys.indexOf('enter') > -1 && !basic){
 if (death){
document.location.reload(true)
   }
   }
 window.requestAnimationFrame(afterdeath)

}
window.addEventListener('load', function(event){
animate(0)
afterdeath()})


</script> 
<p id='demo'>Wings,bubble, ice stick , juice, pause button, bush, 'cool' ,bird icon, suns  from <a href="https://www.pinclipart.com/" title="site for free clipart">pinclipart</a><br>
Backgrounds created by Eder Muniz, trees by senderin  , templates by Jannik Boysen and bars, energy , bubble, button, arrow icons by wenrexa(uploaded on <a href="https://itch.io/" title="site for free assets">itch.io</a>)<br> Player animations, rocks by <a href="https://bevouliin.com/" title="bevoulin">bevoulin</a>
<a href="https://imgur.com/upload" title="site for uploading images "><br>Imgur</a> helped in getting these images in my website  
<br>
<a href="https://www.flaticon.com/free-icons/snowflake" title="snowflake icons">Snowflake icons created by photo3idea_studio - Flaticon</a> <br>
All audio was uploaded on   <a href="https://opengameart.org/" title="site for free audio">opengameart</a>
Bg music by <a href="https://opengameart.org/content/summer-adventure-background-music" title="creator of this">Dansevenstar</a> , jump landing sound by MentalSanityOff, jump grunt by IgnasD, ice cream collection sound by fupi, roll sound by Blender Foundation, fall sound  by remaxim, hit sound by qubodup, click sound by <a href="https://opengameart.org/content/menu-selection-click" title="">NenadSimic</a>
footsteps by <a href="https://opengameart.org/content/footsteps-leather-cloth-armor" title="">HaelDB</a>, Powerup collection sound by JaggedStone, pop by farfadet46, flap sound by VishwaJai <br> <br></p>
<button type="button" id='credit' onclick="cred()">Credits</button>
    </body>
</html>
