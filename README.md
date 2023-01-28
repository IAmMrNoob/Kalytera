# Kalytera
    A Roblox FE-Animator

# Documentation
 - Interface
 - Re-animating
 - Exporting
   - How to export
   - How use creator template

## Interface
It's terrible

1. By selecting the buttons in the `Yellow Box` you change tabs

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068635926584119416/image.png)

2. Proceeding to select Animator
you'll see that in the `Orange Box` the selected body part that youre animating and in the `Green Box` are the values that you can edit you can also use the seekbars(or whatever you call it)

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068637839673274458/image.png)
    How are the seekbars(like the one in the `Green Box`) ordered in the animators

    The seekbars only have a range of -10 to 10

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068658757145464882/image.png)

## Re-animating

1. Going back to the info page in the `Red Box` you'll see 2 Re-animation buttons`[currently R6 only]` R6D is Permadeath that has fling other is just normal yk 

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068634967262908467/image.png)

    I chose permadeath for this one(you can pick any of them) on that topic
    permadeath allows you to animate any part of the body you also need to wait a few seconds, but the one without permadeath you don't need to wait a second and you can't animate the head cause the head is needed for you to stay alive

2. After picking an option you'll see your body in a single state but by changing one of the values it moves in its direction.

    ![](https://media.discordapp.net/attachments/964747509379506259/1068657332956971028/image.png)

3. Same result with the hat animator for when i changed the X position`(Red Box)` for the hat.

    The hats in the `Yellow Box` is the one you're currently animating.
    In the `Blue Box` you'll see the word head which is what the hat is attached to. Bellow the `Blue Box` you'll see "Destroy Mesh" when pressed it removes your hat's mesh which is irreverseble after pressing it.
    ![](https://media.discordapp.net/attachments/964747509379506259/1068662942293311508/image.png)

    Scrolling down you'll see how theyre are some new adjustable values for the hats which are the C1 properties for the hats i wont add this to the body animator(idk for sure)

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068665518770372618/image.png)

## Exporting
### How to export
 - Exporting Body Animation
    1. Press "copy template" then paste it in your executer

        ![](https://media.discordapp.net/attachments/964747509379506259/1068673270083227688/image.png)

    2. Scrol down till you see this`(Red Box)` this is where you place the CFrame lerps

        ![](https://media.discordapp.net/attachments/964747509379506259/1068676019231391866/image.png)

    3. Now press "copy body" then paste it in one of the states i chose the idle state and pasted my lerp inside it

        ![](https://media.discordapp.net/attachments/964747509379506259/1068677095460438056/image.png)
    
 - Exporting Hat Animation
   1. Select the hat(s) that you were animating then paste it in your executer one by one press "copy hat config"
   
       ![](https://media.discordapp.net/attachments/964747509379506259/1068680666658635858/image.png)
   
       ![](https://media.discordapp.net/attachments/964747509379506259/1068680607246336070/image.png)
   
   2. Then paste the hat config above "-----Place hat configs and changes above this line-----" and it should look like this after placing the config you dont need to add it again and the hat should be ready for lerping
   
       ![](https://media.discordapp.net/attachments/964747509379506259/1068681683261472841/image.png)
   
   3. Now press "copy hat lerp" then paste it in one of the states since i "made" a idle and now i wanted my hat to move with that animation i will place i it with my body lerp it should look like this
   
       ![](https://media.discordapp.net/attachments/964747509379506259/1068683907165343795/image.png)
### How to use template creator
Template creator was one of the 1st thing i thought of when i was think of making the animator since release (v1.0) 

I havent updated it or do anything with it but it is also still in works right now (v1.0c)

I'll update it soon when i think of something for it

 1. After making the animations of the body and hat(s) you want to select the hats that you animated and press include hats it's TId`[Texture Id]` should appear below that it was included

    >Quick note when you include the hat you cant remove it and you also dont need to add it again but ill soon add a button to remove a sellected hat(idk why but yeah)

    ![](https://media.discordapp.net/attachments/964747509379506259/1068689188100259950/image.png)
    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068690018471772170/image.png)

 2. After Doing Step[1] select which state the animation should be in `Red Box` i chose idle then below it press "add animation + included hats" and it'll add the idle animation with the hats that are included for the template creator

    ![](https://cdn.discordapp.com/attachments/964747509379506259/1068692625173004288/image.png)

 3. Whenever you finish filling some or all you can scroll down and press "copy created template"

    if you left some animations opened it is recomended to just remove those from the tempalte when pasted in your executer as they have default animations


    ![](https://media.discordapp.net/attachments/964747509379506259/1068694182400635010/image.png)

    ![](https://media.discordapp.net/attachments/964747509379506259/1068694959416430672/image.png)
