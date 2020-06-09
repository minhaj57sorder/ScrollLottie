# ScrollLottie
Use GSAP ScrollTrigger to scroll through a Lottie animation with your mouse or scrollbar

## Dependencies
Greensock GSAP 3.x
https://cdnjs.com/libraries/gsap

Greensock ScrollTrigger (paid plugin)
https://greensock.com/scrolltrigger

Lottie player
https://cdnjs.com/libraries/bodymovin


### Codepen demo
https://codepen.io/chrisgannon/pen/7e302171605cbc4274ce44733189ffe9 

### Useage
    //ScrollLottie (targetDIV, lottieJSONPath, easeDuration, speed);

    ScrollLottie({
     target: '#animationWindow',
     path: 'https://assets.codepen.io/35984/NASA_Worm_logo_scrollTrigger.json', 
     duration: 4, 
     speed: 'slow'
    })

