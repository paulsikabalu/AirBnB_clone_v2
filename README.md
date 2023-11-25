<h1 style="text-align: center;">HBNB - The Console</h1>

<p>This repository encapsulates the preliminary phase of a student project aimed at constructing a replica of the AirBnB website. In this phase, a backend interface, referred to as the console, is established to manage program data. The console commands empower the user to create, update, and destroy objects, alongside administering file storage. The storage persistence between sessions is achieved through JSON serialization/deserialization.</p>

<hr>

<h3 style="text-align: center;">Repository Contents</h3>

<table style="width:100%; border-collapse: collapse; margin: 20px 0;">
    <tr>
        <th>Tasks</th>
        <th>Files</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>0: Authors/README File</td>
        <td><a href="#">AUTHORS</a></td>
        <td>Project authors</td>
    </tr>
    <!-- Additional rows omitted for brevity -->
</table>

<br>
<br>

<h2 style="text-align: center;">General Use</h2>

<ol>
    <li>First, clone this repository.</li>
    <li>Once the repository is cloned, locate the "console.py" file and run it as follows:
        <pre>/AirBnB_clone$ ./console.py</pre>
    </li>
    <li>When this command is run, the following prompt should appear:
        <pre>(hbnb)</pre>
    </li>
    <li>This prompt designates that you are in the "HBnB" console. There are various commands available within the console program.</li>
</ol>

<h4>Commands</h4>

<ul>
    <li><code>create</code> - Creates an instance based on the given class</li>
    <li><code>destroy</code> - Destroys an object based on class and UUID</li>
    <!-- Additional commands omitted for brevity -->
</ul>

<h4>Alternative Syntax</h4>

<p>Users can issue console commands using an alternative syntax:</p>

<pre>
Usage: &lt;class_name&gt;.&lt;command&gt;([&lt;id&gt;[name_arg value_arg]|[kwargs]])
</pre>

<p>Advanced syntax is implemented for the following commands:</p>

<ul>
    <li><code>all</code> - Shows all objects the program has access to, or all objects of a given class</li>
    <!-- Additional commands omitted for brevity -->
</ul>

<br>
<br>

<h2 style="text-align: center;">Examples</h2>

<h3>Primary Command Syntax</h3>

<h5>Example 0: Create an object</h5>

<pre>
Usage: create &lt;class_name&gt;
<span>(hbnb) create BaseModel</span>
<span>(hbnb) create BaseModel</span>
3aa5babc-efb6-4041-bfe9-3cc9727588f8
<span>(hbnb)</span>
</pre>


<h3>Alternative Syntax</h3>

<h5>Example 0: Show all User objects</h5>


