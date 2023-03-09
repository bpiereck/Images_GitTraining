<!--
author:   Bruna Piereck

email:    bruna.piereckmoura@vib.be

version:  1.0.1

language: en

narrator: US English Female

comment:  
    This workshop will take you through the basic use of Git and GitHub. Git is a free and open source distributed version-control system designed to maintain code, track changes, recover old versions and collaborate with other developers. 
    
    **Objectives:**
    Get you started with Git from zero (note that if you already use Git, this workshop will be too basic for you). We'll explore Git on the command-line and its interaction with GitHub. (1.) Introduction, set-up & configurations; (2.) Working locally: Create a repository, clone, edit, staging commits, commit & push
    3.Working with your history & logs; (4.) Working in a project: Branching & pull requests; (5.) During the workshop we also briefly discuss how you can setup a collaboration project.
-->

# Introduction to Git & GitHub

![Cover Image](https://github.com/bpiereck/Images_GitTraining/blob/master/images/cover_intro.svg)


### slide 1


1. Lists
2. ordered or

   * unordered
   * ones ...


| Header 1   | Header 2   |
| :--------- | :--------- |
| Item 1     | Item 2     |


Images:

![images](https://farm2.static.flickr.com/1618/26701766821_7bea494826.jpg)


### Slie 2 

     --{{0}}--
But you can also include other features such as spoken text.

      --{{1}}--
part 1: Insert any kind of audio file:

?[audio](https://bigsoundbank.com/UPLOAD/mp3/1068.mp3)

     --{{2}}--
part 2: Even videos or change the language completely.

       {{2-3}}
!?[video](https://www.youtube.com/watch?v=bICfKRyKTwE)


      --{{3 Russian Female}}--
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном
Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по
разметке текста в электронных письмах...


    {{3}}
Type "voice" to see a list of all available languages.


### Styling

<!-- class = "animated rollIn" style = "animation-delay: 2s; color: purple" -->
The whole text-block should appear in purple color and with a wobbling effect.
Which is a **bad** example, please use it with caution ...
~~ only this is red ;-) ~~ <!-- class = "animated infinite bounce" style = "color: red;" -->

## Charts

Use ASCII-Art to draw diagrams:

                                    Multiline
    1.9 |    DOTS
        |                 ***
      y |               *     *
      - | r r r r r r r*r r r r*r r r r r r r
      a |             *         *
      x |            *           *
      i | B B B B B * B B B B B B * B B B B B
      s |         *                 *
        | *  * *                       * *  *
     -1 +------------------------------------
        0              x-axis               1

## Quizzes

### A Textquiz

What did the **fish** say when he hit a **concrete wall**?

    [[dam]]

### Multiple Choice

Just add as many points as you wish:

    [[X]] Only the **X** marks the correct point.
    [[ ]] Empty ones are wrong.
    [[X]] ...

### Single Choice

Just add as many points as you wish:

    [( )] ...
    [(X)] <-- Only the **X** is allowed.
    [( )] ...


## Executable Code

You can make your code executable and define projects:

``` js     -EvalScript.js
let who = data.first_name + " " + data.last_name;

if(data.online) {
  who + " is online"; }
else {
  who + " is NOT online"; }
```
``` json    +Data.json
{
  "first_name" :  "Sammy",
  "last_name"  :  "Shark",
  "online"     :  true
}
```
<script>
  // insert the JSON dataset into the local variable data
  let data = @input(1);

  // eval the script that uses this dataset
  eval(`@input(0)`);
</script>


## More

Find out what you also can do ...

https://LiaScript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md