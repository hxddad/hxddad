<p align="center">
  <img src="matrix.gif" alt="Matrix GIF">
</p>

<div style="background-color: #f4f4f4; padding: 10px; border-radius: 5px; font-family: monospace;">
<pre style="color: #d63384;">#include &lt;iostream&gt;</pre>
<pre style="color: #d63384;">#include &lt;vector&gt;</pre>
<pre style="color: #d63384;">#include &lt;string&gt;</pre>
<pre style="color: #0000ff;">using namespace std;</pre>

<pre style="color: #008000;">class Person {</pre>
<pre style="color: #008000;">private:</pre>
<pre style="color: #0000ff;">    string name;</pre>
<pre style="color: #0000ff;">    string occupation;</pre>
<pre style="color: #0000ff;">    vector&lt;string&gt; interests;</pre>
<pre style="color: #0000ff;">    string motto;</pre>

<pre style="color: #008000;">public:</pre>
<pre style="color: #008000;">    // Constructor</pre>
<pre style="color: #0000ff;">    Person(string name, string occupation, vector&lt;string&gt; interests, string motto) {</pre>
<pre style="color: #0000ff;">        this-&gt;name = name;</pre>
<pre style="color: #0000ff;">        this-&gt;occupation = occupation;</pre>
<pre style="color: #0000ff;">        this-&gt;interests = interests;</pre>
<pre style="color: #0000ff;">        this-&gt;motto = motto;</pre>
<pre style="color: #0000ff;">    }</pre>

<pre style="color: #008000;">    // Method to display bio</pre>
<pre style="color: #0000ff;">    void bio() {</pre>
<pre style="color: #0000ff;">        cout &lt;&lt; "👋 Hi, I'm " &lt;&lt; this-&gt;name &lt;&lt; ", a " &lt;&lt; this-&gt;occupation &lt;&lt; " who loves ";</pre>
<pre style="color: #0000ff;">        for (size_t i = 0; i &lt; this-&gt;interests.size(); ++i) {</pre>
<pre style="color: #0000ff;">            cout &lt;&lt; this-&gt;interests[i];</pre>
<pre style="color: #0000ff;">            if (i &lt; this-&gt;interests.size() - 1) cout &lt;&lt; ", ";</pre>
<pre style="color: #0000ff;">        }</pre>
<pre style="color: #0000ff;">        cout &lt;&lt; ". My motto: \"" &lt;&lt; this-&gt;motto &lt;&lt; "\"." &lt;&lt; endl;</pre>
<pre style="color: #0000ff;">    }</pre>
<pre style="color: #008000;">};</pre>

<pre style="color: #0000ff;">int main() {</pre>
<pre style="color: #0000ff;">    Person me("Yazan", "Developer", {"coding", "open source", "AI"}, "Keep it simple, but significant.");</pre>
<pre style="color: #0000ff;">    me.bio();</pre>
<pre style="color: #0000ff;">    return 0;</pre>
<pre style="color: #0000ff;">}</pre>
</div>
<!--
<h1 align="center">Hi👋, I'm Yazan</h1>
<h3 align="center">An aspiring developer from Toronto 🇨🇦</h3>

- 📚 I'm a 3rd year <a href="https://lassonde.yorku.ca/academics/software-engineering" target="_blank">Software Engineering (B.Eng)</a> student at York University in Toronto!
- 📄 Check out my resume: <a href="https://github.com/hxddad/resume/blob/main/yazan_haddad_resume.pdf" target="_blank">here</a>, as I'm currently looking for a Summer 2025 internship.
- ⚡ Fun fact: **I currently have 520+ hours on Halo: MCC**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/hxddad" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="hxddad" height="30" width="40" /></a>
<a href="https://www.leetcode.com/hxddad" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="hxddad" height="30" width="40" /></a>
<a href="https://discord.gg/https://discord.gg/Uu88sQ2vfj" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="https://discord.gg/Uu88sQ2vfj" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>
//-->
