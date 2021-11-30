<!DOCTYPE HTML>

<html>

<head>
<title>PastaMath</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Arvo&family=Lobster+Two&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
<script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous">
</script>
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-MML-AM_CHTML"></script>

<meta charset="utf-8">

<style>

    @-webkit-keyframes fadeIn {
        from {
            opacity: 0.0;
        }
        to {
            opacity: 1.0;
        }
    }

    h2 {
        
        font-family: 'Arvo', serif;
        text-shadow: 2px 2px #827F81;
        padding: 10px;
        
    }

    nav {
        padding: 20px;
        background-color: #403E3F;
        overflow: auto;
        text-align: center;
    }

    
    button {
        margin: 10px;
        width: 20%;
        background-color: rgb(148, 143, 144);
        color: white;
        border-color: rgb(148, 143, 144);
        padding-right: 15px;
        padding: 10px;
        text-transform: uppercase;
        box-shadow: 2px 10px 8px rgb(194, 194, 194);
        transition: 0.7s ease;
    }

    button:hover {
        background-color: white;
        cursor: pointer;
        color: black;
        border-color: black
    }


    @media screen and (max-width: 500px) {
        button {
            float: none;
            display: center;
            width: 30%;
        }

        nav {
            text-align: center;
            float: none;
            width: 100%;
            
        }

        p {
            text-align: center;
        }

        h2 {
            text-align: center;
        }
        code {
            text-align: center;
        }
    }

    u {
        text-shadow: 2px 2px 8px #888888
    }

    p {
        font-family: 'Arvo', serif;
    }

    a {
        color: black;
        text-decoration: none;
        transition: 0.5s ease;
    }

    a:hover {
        color: #094899;
    }

    code {
        font-size: 20px;
    }

    pre {
        overflow: auto;
        border: 0.5px solid rgb(199, 199, 199);
        box-shadow: 2px 10px 8px rgb(194, 194, 194);
        border-radius: 4px;
        margin-top: 40px;
        margin-left: 45px;
        margin-right: 45px;
        font-size: 18px;
    }

    #title {
        text-align: center;
        font-family: 'Arvo', serif;
        text-shadow: 2px 2px 8px #827F81;
        padding: 10px;
        border-bottom: black 2px solid;
        box-shadow: 10px 10px 8px #888888
    }

    .scene {
        margin: 30px;
    }

    .other-title {
        text-align: center;
        font-family: 'Arvo', serif;
        text-shadow: 2px 2px 8px #827F81;
        padding: 10px;
    }

</style>



</head>

<body>

    <nav>

        <button onClick="pageChange(0)"><i class="fa fa-fw fa-home"></i> Home</button>
        <button onClick="pageChange(1)"><i class="fas fa-lightbulb"></i> Practice</button>
        <button onClick="pageChange(2)">© Credits</button>
                
    </nav>

    <h1 id = "title">Pasta Math</h1>  

    <div class = "scene">
        <h2><u>Introduction</u></h2>

        <p>Hello there. My name is Noah. I'm not an official math teacher,
        but I am practicing my webpage building skills. Through this website,
        you will be able to learn everything there is to know about Algebra 1
        and Geometry.
        </p>

        <h2><u>I don't know how to use this?</u></h2>
        
        <p>It's pretty easy. Scroll down for links to all the different
        topics. That's it.</p>

        <h2><u>Algebra 1</u></h2>

        <p><a href = 'javascript:pageChange(3);'>Algebra Basics</a> 
        <p><a href = 'javascript:pageChange(4);'>Solving equations & inequalities</a></p>
        <p><a href = 'javascript:pageChange(5);'>Linear equations & graphs </a>
        <p><a href = 'javascript:pageChange(6);'>Forms of linear equations</a>
        <p><a href = 'javascript:pageChange(7);'>Systems of equations</a>
        <p><a href = 'javascript:pageChange(8);'>Inequalities Again</a>
        <p><a href = 'javascript:pageChange(9);'>Functions</a>
        <p><a href = 'javascript:pageChange(10);'>Sequences</a>
        <p><a href = 'javascript:pageChange(11);'>Absolute value & piecewise functions</a>
        <p><a href = 'javascript:pageChange(12);'>Exponents & radicals</a>
        <p><a href = 'javascript:pageChange(13);'>Exponential growth & decay</a>
        <p><a href = 'javascript:pageChange(14);'>Quadratics: Multiplying & factoring</a>
        <p><a href = 'javascript:pageChange(15);'>Quadratic functions & equations</a>

    </div>

    <div class = "scene">
        <h2><u>Practice Problems</u></h2>

        <p>This page has all the practice problems you'll need with each lesson.
        Click on a link to begin practice problems.</p>

        <p><a href = 'javascript:pageChange(16);'>Algebra Basics</a> 
        <p><a href = 'javascript:pageChange(17);'>Solving equations & inequalities</a></p>
        <p><a href = 'javascript:pageChange(18);'>Linear equations & graphs </a>
        <p><a href = 'javascript:pageChange(19);'>Forms of linear equations</a>
        <p><a href = 'javascript:pageChange(20);'>Systems of equations</a>
        <p><a href = 'javascript:pageChange(21);'>Inequalities Again</a>
        <p><a href = 'javascript:pageChange(22);'>Functions</a>
        <p><a href = 'javascript:pageChange(23);'>Sequences</a>
        <p><a href = 'javascript:pageChange(24);'>Absolute value & piecewise functions</a>
        <p><a href = 'javascript:pageChange(25);'>Exponents & radicals</a>
        <p><a href = 'javascript:pageChange(26);'>Exponential growth & decay</a>
        <p><a href = 'javascript:pageChange(27);'>Quadratics: Multiplying & factoring</a>
        <p><a href = 'javascript:pageChange(28);'>Quadratic functions & equations</a>

    </div>

    <div class = "scene">
        <h2><u>Yo</u></h2>
    </div>

    <div class = "scene">
        <h2><u>Lesson 1: Basic Algebra</u></h2>

        <p>In this lesson, I will teach the basics of Algebra. First, I'll
        give a brief overview of variables, explaining what they are. Then, I'll
        teach how to substitute variables into equations, combine like terms, then
        finally finish with solving x (at least the basics).</p>

        <h2 class = "other-title"><u>Intro to variables</u></h2>

        <p>To make it simple. A variable is a letter that takes the place of
        any real number. The most popular being <code>"x"</code>. Here
        is an example of what it would look like.<br><br><code>x = 20</code><br><br>
        As you can see, "x" is representing the number 20. The cool thing is that
        "x" can be represented as any <em>real</em> number (notice emphasis on the
        real. This means you can't have "x" be an imaginary number).<br><br>If you
        notice something, "x" looks like a multiplying sign. If you ever run into
        this problem, the best way to fix it is to just put an asterick <strong>"*"</strong>
        symbol as the multiplying sign. Here's an example: <br><br><code>x * 5 = 15</code><br><br>
        Another way people do it is by putting the coefficient and variable next to each
        other like this (make sure the number goes in front of the variable):<br><br><code>5x</code><br><br>It's the same exact thing as
        5 * x.</p>

        <h2 class = "other-title"><u>Substituting variables</u></h2>

        <p>In the last topic, I discussed what variables were. In this topic, I'm
        going to be showing you how variables work with equations. We'll make the
        variables, then make an expression, the solve for it.<br><br>Let's start
        out with something simple. I'm going to say the following:<br><br>
        <code>If x = 5, solve for the expression x + 5.</code><br><br>Going back
        to our knowledge of variables, this is saying that since x = 5, we can
        substitute 5 back into the expression instead of x. So then it'll be as follows:<br><br>
        <code>x = 5<br><br>(5) + 5.</code><br><br>5 + 5 = 10, so the answer is 10.<br><br>
        Let's do a harder one.<br><br><code>If x = 5, solve the expression (x * 3) / 5</code><br><br>
        If we substitute 5 for x again, we get this.<br><br><code>x = 5<br><br>(5 * 3) / 5<br><br>
        15 / 5 = 3</code><br><br>Since 15 / 5 = 3, then our answer is 3.</p>

        <h2 class = "other-title"><u>Combining like terms</u></h2>

        <p>In this topic, I will be discussing how to combine like terms.<br><br>
        What is a like term? A like term is when the coefficient and/or variables (if there are any)
        are the same. Still confused? Here's an example.<br><br><code>1. 2x + 2x (These are like terms)<br>
        2. 5x - 2x (These are like terms)<br>3. 5x - 5 (These are not like terms).</code><br><br>
        Why is the third one not a like term? They have both are real coefficients, but they
        don't have the same variable. The same applies if you have something like this:<br><br><code>2x + 2y</code><br><br>
        Once again, they don't have the same variables, therefore, they aren't like terms.<br><br>
        Combining like terms are <em>very</em> easy. You simply add the coefficients, then
        add the variables next to them. Here's an example:<br><br><code>3y + 7y = 10y</code><br><br>
        Think of it this way. Let's say you had 3 apples (or y), and you added 7 apples (or y). How
        many apples would you have? You would have 10 apples (or y).<br><br>Let's do one more example:
        <pre>

Solve the equation below:

7x + 11x = 18x

        </pre>

        <p>Here's a hard example:</p>

        <pre>

Solve the equation below:

7y<sup>2</sup> - 4y<sup>2</sup> = 3y<sup>2</sup>

        </pre>

        <h2 class = "other-title"><u>Solve for X</u></h2>

        <p>Now that you've gotten the hang of variables, let's see if we can try
        to solve for x. This one will be a little hard to get the hang of, but I'll
        try my best to explain. Let's begin.<br><br>Let's see an example of solving for
        x.<br><br><code>Solve for x.<br><br>x + 6 = 20</code><br><br>Let's take
        this one at time. First, I'll need to explain something though. If you notice,
        in order to solve for x, we need all of the non-x terms on one side, and leave
        x by itself on the other side of the equal sign. But how do we do that?<br><br>
        There's a "6" in the way, so we need to get rid of it. How? Well, if we subtracted
        6 on the left side, what do have left? We would get x + 0, since 6 - 6 = 0.
        But wait. If we do this to just one side, we have a problem. The equation said
        that x + 6 = 20, but when we subtracted and got rid of the 6, now the it just
        says x = 20? If we use substituting to check our answer, what do we get? Let's see:<br><br>
        <pre>

x + 6 = 20
  - 6        (First we subtract 6 to get rid of the 6)
___________
 x   =  20

Now we substitute 20 back into the equation using substitution.

(20) + 6 = 20

26 = 20?

        </pre>
        <p>
        As you can see, 26 does not equal 20. So what did we do wrong? We didn't do
        to <em>both</em> sides of the equation. Let's try that and see what happens.
        </p>      
        <pre>

x + 6 = 20
  - 6 = -6    (First we subtract 6 from <em>both</em> sides of the equation)
__________

 x  = 14

Now we can substitute 14 into the equation, and you see what happens.

(14) + 6 = 20

20 = 20!

        </pre>
        <p>
        As you can see, it worked! This is because when we use Algebra to manipulate the
        equation, we change up the equation while we're at it. So to balance it out,
        whatever we do to one side, we <strong><em>have</em></strong> to do it to the
        other side as well.
        </p>    

        <p>Try to solve this one on your own. (Hint, you might have to remember like terms)<br><br>
        <code>5x + 2x - 4 = 17</code></p> 

</p>

        <h2 class = "other-title"><u>Conclusion</u></h2>

        <p>That's it! If you want to nail down these concepts, try to do some
        practice problems on the top. I'll see you in the next topic! Pound it! Noggin! Brooooooo!!!
</p>

<button onClick="pageChange(0)">Back</button>
<button style = "float: right;" onClick="pageChange(4)">Next</button>

</div>

    <div class = "scene">

    <h2><u>Lesson 2: Solving Equations and Inequalities</u></h2>
    
    <p>In this lesson, I'm going to be teaching about how to solve equations when
    the variable is on both sides of the equation, equations using the distribution property, solving
    for equations with other variables, inequalities with multiple steps, and finally
    compound inequalities.</p>

    <h2 class = "other-title"><u>Solving equations with variables on both sides</u></h2>    

    <p>The first thing I want to teach is how to solve for equations if the variable
    is on both sides of the equation. Let's look at an example.</p>

    <pre>
    
    6x - 3 = 4x + 5
    
    </pre>

    <p>Let's figure out how to solve this. The first thing we need to do is to get
    all the numbers on one side, and leave the variable on the other side of the equal
    sign. Let's do that by adding 3 to both side of the equation.

    <pre>

    6x - 3 = 4x + 5
       + 3      + 3
    _______________
      6x = 4x + 8

    </pre>

    <p>Now we can get the other variable to the other side by subtracting 4x by both sides.
    Let's see what happens when we do that.

    <pre>

    6x = 4x + 8
   -4x  -4x
   _____________
      2x = 8

    </pre>

    <p>Finally, we need to get x by itself. If you notice, 2x is the same as
    2 * x, so we just need to divide 2 by both sides, and what do we get?</p>

    <pre>

    2x = 8
    __  ___
     2   2

     x = 4

    </pre>

    <p>Now we can substitute x back into the equation and let's see what happens.</p>

    <pre>

    6(4) - 3 = 4(4) + 5

     24 - 3 = 16 + 5

      21 = 21

    </pre>

    <p>It's correct! As you can see, it takes a little more work, but it gets
    easier. Let's move on to the next topic.</p>

    <h2 class = "other-title"><u>Equations using the distribution property</u></h2>

    <p>In the last topic, we discussed how to solve for equations that
    had variables on both sides of the equal sign. Now we will try to solve
    for variables that need PEMDAS. Let's see an example.</p>

    <pre>

    6(x + 5) = 5(x + 6) 
    </pre>

    <p>If you remember back in pre-algebra, you would need to distribute
    the number outside the parentheses and multiply it by each number inside
    the parentheses. So doing that, here's what it would look like.</p>

    <pre>

    6(x + 8) = 5(x + 6), Mulitply the 6 and 5 by both of the equations inside the parentheses
     
    6x + 48 = 5x + 30,   6 * x = 6x, and 5 * x = 5x, so that's where we got the 5x & 6x
    </pre>

    <p>Now we have variables on both sides, so we just need to solve for x.
    Let's do that.</p>

    <pre>
    
    6x + 48 = 5x + 30
       - 30      - 30      Subtract 30 from both sides  
    _________________
        6x + 18 = 5x

    6x + 18 = 5x
   -5x       -5x           Subtract 5x to get all the x's on one side  
    _____________
      x + 18 = 0

    x + 18 = 0
      - 18 - 18            Subtract 18 from both sides to get x = -18  
    ___________
       x = -18
    </pre>

    <p>Now let's check our answer.</p>

    <pre>

    6(-18) + 48 = 5(-18) + 30

    -108 + 48 = -90 + 30

      -60 = -60
    </pre>

    <p>It's correct! That one was a hard one, but hopefully you understood
    it. Just make sure to practice a lot, and it'll become easier. </p>

    <h2 class = "other-title"><u>Solving for equations with other variables</u></h2>

    <p>Before we begin, I just want you to make sure that you read this several times
    because this topic is pretty hard. In this topic, we'll be discussing on how
    to solve for equations with other unknown variables. Let's begin.</p>

    <p>In the first topic of this lesson, we went into solving variables when the
    variable is on both sides of the equation. Now we're going to look when more
    than one variable is on both sides. Let's start with an easy one.</p>

    <pre>

    Solve for x
    
    6x + 5 = 5y - 4
    </pre>  

    <p>At first, this may seem impossible because we don't know what "y" is. How
    will we solve for y? Well, we aren't going to. What do you mean you may be
    wondering. Well, we just want to solve for x, so we'll get all the y and
    coeffiecents on side of the equation, and x by itself. Let's see what happens:

    <pre>

    Solve for x
    
    6x + 5 = 5y - 4
       - 5      - 5   Subtract 5 from both sides to get the 6x by itself
    _______________
      6x = 5y - 9

    6x = 5y - 9
    __   ______       All we have to do is divide 6 by both sides to get the x by itself
     6      6

          5y - 9
    x =   ______      
             6    
    </pre> 

    <p>Sorry for the dividing sign. I'll try to fix that in the next lesson hopefully.
    As you can see, we can't really substitute x back into the equation, since that'll
    get <em>very</em> messy. But we did it. We solved for x. Hopefully this helped
    you understand it. Let's try one with using the distribution property.
    (By the way, I'm using LaTeX as my math equator since from here on out, it'll
    use more equations)</p>

    <p><span class="math-display">\[6(x - 3) = 3(y - 2)\]</span>It's actually
    pretty easy if you're used to the distribution property. Here's how to solve
    it:</p>

    <p>Multiply 6 and 3 by the equations in parentheses<span class="math-display">
    \[6x - 18 = 3y - 6\]</span>Add 18 to both sides.</p>

    <p><span class="math-display">\[6x = 3y + 12\]</span>And then finally
    divide 6 on both sides. <em>Make sure to divide 6 on 3y and 12</em></p>

    <p><span class="math-display">\[x = \frac{3y+12}{6}\]</span>And there we
    have it! As you can see, it's not that hard, as long as you get the concept.
    </p>

    <h2 class = "other-title"><u>Inequalities with multiple steps</u></h2>

    <p>This topic will be a little different. Instead of using equations that say
    that x = c, now we're saying x less than or greater than c (sorry, I can't
    type it right now, but I will). Here's an example of an inequality:

    <p>Solve for x<span class="math display">\[4x + 5 &gt; 21\]</span></p>

    <p>We need to think of it as if it were <span class="math display">
    \[4x + 5 = 21\]</span></p>

    <p>If we think of it that way, then we can solve for x. Let's do that:

    <p>Subtract 5 from both sides of the equation<span class="math display">\[4x + 5 &gt; 21\]</span></p>

    <p>Divide 4 by both sides<span class="math display">\[4x &gt; 16\]</span></p>

    <p><span class="math display">\[x &gt; 4\]</span></p>

    <p>Now you might be thinking, "Let's substitute 4 back in!" Well, hang on,
    if we add 4 back in, then it will be this:

    <p><span class="math display">\[4(4) + 5 &gt; 21\]</span></p>
    <p><span class="math display">\[16 + 5 &gt; 21\]</span></p>
    <p><span class="math display">\[21 &gt; 21\]</span></p>

    <p>Um. Last I checked, 21 was not greater than 21. What we can do is this.
    Since x > 4, x can be equal to any number that is greater than 4, like
    5, 6, 7, 8, etc. That means we can substitute 5 instead, since 5 > 4. Let's
    see what happens if we do that.</p>

    <p><span class="math display">\[4(5) + 4 &gt; 21\]</span></p>
    <p><span class="math display">\[20 + 4 &gt; 21\]</span></p>
    <p><span class="math display">\[24 &gt; 21\]</span></p>

    <p>As you can see, 24 is greater than 21, so we solved for x! Let's do one
    more harder one.</p>

    <p>Solve for y<span class="math display">\[3(y + 5) &gt; 5(y - 4)\]</span></p>
    <p>Distribute<span class="math display">\[3y + 15 &gt; 5y - 20\]</span></p>
    <p>Subtract 5y from both sides<span class="math display">\[-2y + 15 &gt; -20\]</span></p>
    <p>Subtract 15 by both sides<span class="math display">\[-2y &gt; -35\]</span></p>

    <p>I'm going to stop here to tell you something. Here is something you
    need to know. Please put this in your brain and remember it, because it's
    very important. <em>If you have to multipy or divide by a negative number when
    it's an inequality, you have to switch the signs.</em> It'll take a while
    to explain, but if you look it up, then you can see why. But since we're
    dividing by -2, then we switch the signs. Let's do that.</p>

    <p><span class="math display">\[y &lt; 17.5\]</span></p>

    <p>Now let's test it. I'm going to do 3 because it's still less than 17.5
    and all the other number might get hairy. Let's see what happens.</p>

    <p><span class="math display">\[3(3) + 15 &gt; 5(3) - 20\]</span></p>
    <p><span class="math display">\[9 + 15 &gt; 15 - 20\]</span></p>
    <p><span class="math display">\[24 &gt; -5\]</span></p>

    <p>As you can see, 24 > -5, so it worked! One more thing, if you tried
    something greater than 17.5, then it won't work. Try it out for yourself.
    Let's move on to the last topic.</p>

    <h2 class = "other-title"><u>Compound inequalities</u></h2>

    <p>This topic can be tricky sometimes, but let's see a problem.</p>

    <p>Solve for x<span class="math display">\[2x+3≥7 \text{  OR  } 2x+9&gt;11\]</span></p>

    <p>First we need to solve for both inequalities. So let's start there.</p>

    <p>Subtract 3 from both sides<span class="math display">\[2x + 3 ≥ 7\]</span></p>
    <p>Divide 2 by both sides<span class="math display">\[2x \geq 4\]</span></p>
    <p>We did it<span class="math display">\[x \geq 2\]</span></p>

    <p>By the way, it's saying x > or equal to x, meaning x can be 2 as well.
    Now we have to do it to other equation. From here on out, I'll just put
    each step. Hopefully by now you understand the process.</p>

    <p><span class="math display">\[2x + 9 &gt; 11\]</span></p>
    <p><span class="math display">\[2x &gt; 2\]</span></p>
    <p><span class="math display">\[x &gt; 1\]</span></p>

    <p>What this means is that x has to be greater than 2 or 1. Since 2 > 1,
    We can just say that x > 1 is the answer because it satisfies the OR.</p>

    <p>What if it was AND? How would we solve for x? Well the answer is still
    x > 1 because it still satisfies both. x > 1 AND x > 2 is correct, therefore
    x > 1 is the correct answer.</p>

    <h2 class = "other-title"><u>Conclusion</u></h2>

    <p>This was a lot to take in, but I hope this helps you understand this a
    bit better. Try some example problems to help you better understand it.
    I'll see you in the next lesson!</p>

    <button onClick = "pageChange(3);">Back</button>
    <button onClick = "pageChange(5);" style = "float:right;">Next</button>
    
    </div>

    <div class= "scene">
        <h2 class="title"><u>Lesson 3: Linear equations & graphs</u></h2>

        <p>In this lesson, I'm going to be teaching you linear equations.
            I'll be teaching the two-variable linear equations (intro), slope
            and how that works, horizontal and vertical lines, x & y intercepts,
            and applying intercepts and slopes. Let's begin!
        </p>

        <h2 class="other-title"><u>Two-variable linear equations (intro)</u></h2>

        <p>
            In this topic, I'm going to be going over two-variable linear equations,
            which hopefully shouldn't be too hard. Let's begin.
        </p>

        <p>
            This is actually not as bad as you think it would be. Instead of solving 
            for x and y, we're actually just substituting into an equation after solving for x or y, depending on where the question mark is. Let's see 
            an example problem.
        </p>

        <p><span class="math display">\[\text {What is the solution to the equation?} \\

            x + 5 = y \\
            
            (?, 10)\]</span></p>
        
        <p>
            Realize that we are given the point where x = ?
            and y = 10, just like you would see on a graph. If y = 10,
            then all we would have to do is substitute y into the equation,
            then solve for x. Let's see what happens when we do that.
        </p>

        <p><span class="math display">\[x + 5 = 10\]</span></p>
        <p><span class="math display">\[x = 5\]</span></p>

        <p>
            Now let's see if it works. You can do it in your head, but 
            I'll show you anyway.
        </p>

        <p><span class="math display">\[(5) + 5 = (10)\]</span></p>

        <p>
            As you can see, it works! Let's try one more harder:
        </p>
        <p><span class="math display">\[3x + 3y = 25 \\

            (5, ?)\]</span></p>

        <P>
            So now let's substitute 5 for x. Let's see what happens 
            when we do that.
        </P>

        <p><span class="math display">\[3(5) + 3y = 25\]</span></p>
        <p><span class="math display">\[15 + 3y = 25\]</span></p>
        <p><span class="math display">\[3y = 10\]</span></p>
        <p><span class="math display">\[y = \frac{10}{3}\]</span></p>

    <button onClick = "pageChange(4);">Back</button>
    <button onClick = "pageChange(6);" style = "float:right;">Next</button>

    </div>

</body>

<script>

    scenes = document.getElementsByClassName("scene");

    function pageChange(pageNumber) {

        for(var i = 0; i < scenes.length; i++) {
            scenes[i].style.display = 'none';
            scenes[i].style.animation = 'fadeIn 0.5s ease';
        }

        scenes[pageNumber].style.display = 'block';
    };

    pageChange(0);

</script>

</html>



