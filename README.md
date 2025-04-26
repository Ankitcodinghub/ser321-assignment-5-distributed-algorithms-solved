# ser321-assignment-5-distributed-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [SER321 Assignment 5 Distributed Algorithms Solved](https://www.ankitcodinghub.com/product/ser321-assignment-5-distributed-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97697&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SER321 Assignment 5 Distributed Algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h1>Prerequisites</h1>
<ol>
<li>The assigned readings in module 5 on Canvas</li>
<li>Lecture videos from Canvas/ or class</li>
<li>Running and understanding the examples listed on the Canvas Module 5 page</li>
</ol>
<strong>Learning outcomes of this assignment are:</strong>

<ol>
<li>Understand basics of Distributed Algorithms</li>
<li>Evaluate distributed algorithms</li>
<li>Understand the basics of Consensus algorithms</li>
</ol>
<h1>Preliminary things</h1>
I strongly advise you to work on Git and GitHub, to version control and also to practice. If you work on GitHub make sure your repository is private.

Submit your assignment as always on GitHub in the appropriate directory and as zip on Canvas .

<h1>What you definitely need: 15 points</h1>
This part has a lot of points, you cannot receive all 15 points however in case you did not implement things or fulfilled less than 1/3 of the requirements at least partially.

<ol>
<li>You will create one project from scratch, your program needs to have a useful build.gradle file</li>
<li>A README.md
<ol>
<li>Design your calls and user interaction in a way that they are easy.</li>
<li>Include the command how we can run your program and in what order we need to call what in Gradle c) Explain your program</li>
<li>Explain your protocol in detail (you can use any protocol type you want)</li>
<li>Explain your encryption method</li>
<li>Include a list of the requirements you think you fulfilled</li>
<li>As always include a screencast that shows all your functionality – go through all requirements you fulfilled so we can already see it in your screencast if it works before we try it ourselves.</li>
</ol>
</li>
</ol>
<h1>Distributed algorithm (85 points)</h1>
You start this activity from scratch. You can of course use any of the given example code as starter or inspiration.

The idea is to build a very simplified distributed algorithm network to encrypt a sentence. We also include a little simplified consensus algorithm. This is all very simplified just to give you a taste, you do not have to worry about security etc. but you should make sure your program is robust and well implemented.

<h2>Requirements</h2>
In here we will also grade with partial credit if you get part of it going and we can see these parts (based on when we run it, your Readme and your video). If we cannot run it we cannot award points.

You will need different parts that can be started:

<ol>
<li>A Leader: this one is also the one where the user can input data.</li>
<li>Nodes: all nodes have the same code, many nodes can be connected to the one leader.</li>
</ol>
The basic idea is that the user can input a sentence into the leader and that sentence will be split up as <em>numberOfSymbols/nodesInNetwork</em>. Then each node will get a part of that sentence to encrypt from the leader. What encryption you use does not matter as long as it is symbol by symbol. So no matter if it is split up between 1 or 50 nodes the encrypted message should be the same. The node will send the encrypted string back. The leader will then do a check to make sure no node is faulty. To do so the leader will send over an encrypted part and the corresponding decrypted part to each node (to a different one than the one that initially encrypt it) and the node needs to check if it is valid. It will return a yes/no if it thinks the encryption is valid. Only when all nodes return “yes” will the leader put the encrypted sentence back together and return it to the user.

See below for the requirements split up in more detail.

<ol>
<li>(3 points) Leader can be started through <em>gradlerunLeader</em></li>
<li>(3 points) Nodes can be started through <em>gradlerunNode−pPort </em>= <em>X−pLeaderPort </em>= <em>Y </em>(port is its own port, leaderPort the leaders port)</li>
<li>(3 points) At least 3 Nodes should always be connected to the Leader</li>
<li>(2 points) Encryption should not work with less than 3 Nodes</li>
<li>(5 points) The Leader should be able to handle up to 8 Nodes</li>
<li>(3 points) Leader asks the user for a sentence</li>
<li>(4 points) The sentence received is split up based on the number of Nodes. If the sentence cannot be split up evenly then split it up as best as possible</li>
<li>(3 points) Leader sends a part of the sentence to each Node (each Node gets a different part)</li>
<li>(5 points) Leader should send it threaded so that the Nodes work in parallel on the encryption (imagine it is a really complicated encryption algorithm that takes a long time)</li>
<li>(6 points) Node receives the part of the sentence and runs some encryption algorithm (you choose which one)</li>
<li>(4 points) Node sends the encrypted part of the sentence back to Leader</li>
<li>(3 points) Leader receives the encrypted sentence parts</li>
<li>Leader starts a consensus for double checking the result
<ol>
<li>(5 points) Leader sends each Node an encrypted and the corresponding decrypted part of the sentence (make sure it is not the same as the Node initially had – you can just shift)</li>
<li>(5 points) This sending also happens in threads.</li>
<li>(5 points) Node encrypts the string it gets again and matches against the encrypted one it received. If it matches it sends back an ok (or yes).</li>
<li>(8 points) Nodes can be faulty: with a Gradle flag -pFault=1 allow that the node encrypts a received String wrong, thus it would return a “no” when it does the double check.</li>
<li>(10 points) The Leader receives the answers, only when all vote “yes” will the encrypted message be put together again (make sure it is the correct order) and displayed for the customer.</li>
<li>(13 points) If one node votes “no” (or more than one) you need to handle that since it means something if faulty. If the Leader catches this, then they should send a test String (from which it knows the encrypted answer) to the two Nodes which seem to have the discrepancy to check which one is faulty. It should receive an answer and should then eliminate the faulty Node from the Network. If both are faulty, remove both.</li>
</ol>
</li>
<li>Overall good error handling, no crashing, users are informed of what is going on.</li>
</ol>
Should go without saying. We might deduct up to 10% if this is bad.

&nbsp;
