---
layout: two-cols
clicks: 4
---

<div class='mono-font'>
<v-clicks>

You want it to <span class='blue'>work</span><br><br><br>

You want it to be <span class='red'>fast</span> <br><br><br>

You want it to be <span class='orange'>easy to understand</span> <br><br><br>

You want it to be <span class='yellow'>scalable</span> 

</v-clicks>
</div>

<div class='flex flex-col pt-10'>
    <div class='my-1 w-2 h-2 bg-blue rounded-xl animate-bounce' style='animation-duration: 0.7s' />
    <div class='my-1 w-2 h-2 bg-red rounded-xl animate-bounce' style='animation-duration: 0.8s' />
    <div class='my-1 w-2 h-2 bg-orange rounded-xl animate-bounce' style='animation-duration: 0.9s' />
    <div class='my-1 w-2 h-2 bg-yellow rounded-xl animate-bounce' style='animation-duration: 1s' />
</div>

::right::

<div class='mono-font text-xs'>

<p class='blue' v-click="1"> Google<br> YouTube<br> ChatGPT </p>
<p class='red' v-click="2"> Algorithm <br> Data structure </p>
<p class='orange pt-7' v-click="3"> Clean Code </p>
<p class='yellow pt-11' v-click="4"> Design Pattern <br> SOLID principal <br> Coding paradigm (OOP, Functional, etc)</p>

</div>
