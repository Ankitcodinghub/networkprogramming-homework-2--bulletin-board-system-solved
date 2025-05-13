# networkprogramming-homework-2--bulletin-board-system-solved
**TO GET THIS SOLUTION VISIT:** [NetworkProgramming Homework 2 –Bulletin Board System Solved](https://www.ankitcodinghub.com/product/networkprogramming-homework-2-bulletin-board-system-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92805&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;NetworkProgramming Homework 2 –Bulletin Board System Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Homework 2 – Bulletin Board System: Part 2

Description

Continuing the first part, you are asking to implement the functions of the Bulletin Board System (BBS) server.

Requirement

The service accepts the following commands and at least 10 clients:

When client enter command incompletely E.g., missing parameters, the server should show command format for client.

</div>
</div>
<div class="layoutArea">
<div class="column">
Command format create-board &lt;name&gt;

create-post &lt;board-name&gt; –title &lt;title&gt; –content &lt;content&gt;

(command is in the same line )

list-post &lt;board-name&gt; ##&lt;key&gt;

read &lt;post-id&gt;

delete-post &lt;post-id&gt;

</div>
<div class="column">
Description

Create a board which named &lt;name&gt;.

&lt;name&gt; must be unique.

If Board’s name is already used, show failed message, otherwise it is success.

Must be logged in when creating board’s name

Create a post which title is &lt;title&gt; and content is &lt;content&gt;.

Use –title and –content to separate titles and content.

&lt;tilte&gt; can have space but only in one line. &lt;content&gt; can have space, and key in &lt;br&gt; to indicate a new line.

List all posts in a board named &lt;board-name&gt; &lt;key&gt; is a keyword, use ## &lt;key&gt; to do advanced query.

Show the post which ID is &lt;post-id&gt;.

Delete the post which ID is &lt;post-id&gt;.

Only the post owner can delete the post.

If the user is not the post owner, show failed message, otherwise it is success.

</div>
<div class="column">
Success Fail (1) Fail (2) Success

Fail (1) Fail (2)

Success

ID &lt;ID1&gt;

Fail

Fail Success Fail (1) Fail (2) Fail (3)

</div>
<div class="column">
Result

Create board successfully.

Board already exist. Please login first.

Create post successfully.

Board does not exist. Please login first.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
list-board ##&lt;key&gt;

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
List all boards in BBS.

&lt;key&gt; is a keyword, use ## &lt;key&gt; to do advanced query.

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Index Name Moderator &lt;Index1&gt; &lt;Name1&gt; &lt;Moderator1&gt;

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Title &lt;Title1&gt;

</div>
<div class="column">
Author Date &lt;Author1&gt; &lt;Date1&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
Board does not exist.

Post does not exist. Delete successfully. Please login first. Post does not exist. Not the post owner.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Success

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Author :&lt;Author1&gt; Title :&lt;Title1&gt; Date :&lt;Date1&gt; —

&lt;content&gt;

—

&lt;User1&gt; : &lt;Comment1&gt;

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
update-post &lt;post-id&gt; –title/content &lt;new&gt;

comment &lt;post-id&gt; &lt;comment&gt;

exit

Scenario

</div>
<div class="column">
Update the post which ID is &lt;post-id&gt;.

Use — to decide which to modify, title or content, and replaced by &lt;new&gt;.

Only the post owner can update the post.

If the user is not the post owner, show failed message, otherwise it is success.

Leave a comment &lt; comment &gt; at the post which ID is &lt;post-id&gt;

Close connection.

</div>
<div class="column">
Success

Fail (1)

Fail (2)

Fail (3)

Success Fail (1) Fail (2)

</div>
<div class="column">
Update successfully. Please login first. Post does not exist. Not the post owner.

Comment successfully. Please login first.

Post does not exist.

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
******************************** ** Welcome to the BBS server. **

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>bash$ telnet 127.0.0.1 7890
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
NP_HW

Please login first.

% register Bob bob@qwer.asdf 123456 Register successfully.

% register Sam sam@qwer.com 654321 Register successfully.

% login Bob 123456

Welcome, Bob.

% create-board NP_HW

Create board successfully.

% create-board NP_HW

Board already exist.

% create-board OS_HW

Create board successfully.

% create-board FF

Create board successfully.

% list-board

Index Name

<ol>
<li>1 &nbsp;NP_HW Bob</li>
<li>2 &nbsp;OS_HW Bob</li>
<li>3 &nbsp;FF_HW Bob</li>
</ol>
% list-board ##HW

Index Name

1 NP_HW Bob 2 OS_HW Bob

</div>
</div>
<div class="layoutArea">
<div class="column">
Moderator

</div>
</div>
<div class="layoutArea">
<div class="column">
Moderator

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
% create-board

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
% create-post NCTU –title About NP HW_2 –content Help!&lt;br&gt;I have some problem!

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Board does not exist.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
% create-post

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Create post successfully.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
% create-post

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Create post successfully.
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
NP_HW

</div>
</div>
<div class="layoutArea">
<div class="column">
NP_HW

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>--title About NP HW_2 --content Help!&lt;br&gt;I have some problem!
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>--title HW_3 --content Ask!&lt;br&gt;Is NP HW_3 Released?
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
% list-post NP

Board does not exist. % list-post NP_HW

% list-post NP_HW ##HW_2

% read 888

Post does not exist. % read 1

Author :Bob

Title :About NP HW_2 Date :2020-03-31

—

<pre>    Help!
    I have some problem!
</pre>
—

% update-post 888 –title NP HW_2 Post does not exist.

% update-post 1 –title NP HW_2 Update successfully.

% read 1

Author :Bob

Title :NP HW_2 Date :2020-03-31 —

<pre>    Help!
    I have some problem!
    --
</pre>
% logout

Bye, Bob.

% login Sam 654321 Welcome, Sam.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
1 –content

<pre>Not the post owner.
</pre>
% delete-post 1 Not the post owner.

<pre>Post does not exist.
</pre>
Comment successfully. % read 1

Author :Bob

Title :NP HW_2 Date :2020-03-31 —

<pre>    Help!
    I have some problem!
    --
    Sam: Ha! ha! ha!
</pre>
% create-board Hello Create board successfully. % list-board

</div>
</div>
<div class="layoutArea">
<div class="column">
% update-post

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
% comment

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<pre>888 Ha! ha! ha!
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
% comment

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1 Ha! ha! ha!

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Index Name

<ol>
<li>1 &nbsp;NP_HW Bob</li>
<li>2 &nbsp;OS_HW Bob</li>
<li>3 &nbsp;FF_HW Bob</li>
<li>4 &nbsp;Hello Sam</li>
</ol>
% logout

Bye, Sam.

% login Bob 123456 Welcome, Bob.

% delete-post 1 Delete successfully. % read 1

Post does not exist. % logout

Bye, Bob.

% exit

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Ha!&lt;br&gt;ha!&lt;br&gt;ha!
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Moderator

</div>
</div>
</div>
</div>
