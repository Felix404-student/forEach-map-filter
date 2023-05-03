# forEach-map-filter
forEach / map / filter practice lesson for UMass/Springboard bootcamp
written in Javascript

Assignment:
Write the functions necessary for the tests to pass, you can find the tests in the downloaded code.

<div class="section" id="foreach">
<h2>forEach</h2>
<div class="section" id="doublevalues">
<h3>doubleValues</h3>
<p>Write a function called doubleValues which accepts an array and returns a new array with all the values in the array passed to the function doubled</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">doubleValues</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [2,4,6]</span>
<span class="nx">doubleValues</span><span class="p">([</span><span class="mi">5</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">10</span><span class="p">])</span> <span class="c1">// [10,2,4,6,20]</span>
</pre></div>
</div>
</div>
<div class="section" id="onlyevenvalues">
<h3>onlyEvenValues</h3>
<p>Write a function called onlyEvenValues which accepts an array and returns a new array with only the even values in the array passed to the function</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">onlyEvenValues</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [2]</span>
<span class="nx">onlyEvenValues</span><span class="p">([</span><span class="mi">5</span><span class="p">,</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">10</span><span class="p">])</span> <span class="c1">// [2,10]</span>
</pre></div>
</div>
</div>
<div class="section" id="showfirstandlast">
<h3>showFirstAndLast</h3>
<p>Write a function called showFirstAndLast which accepts an array of strings and returns a new array with only the first and last character of each string.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">showFirstAndLast</span><span class="p">([</span><span class="s1">&#39;colt&#39;</span><span class="p">,</span><span class="s1">&#39;matt&#39;</span><span class="p">,</span> <span class="s1">&#39;tim&#39;</span><span class="p">,</span> <span class="s1">&#39;test&#39;</span><span class="p">])</span> <span class="c1">// [&quot;ct&quot;, &quot;mt&quot;, &quot;tm&quot;, &quot;tt&quot;]</span>
<span class="nx">showFirstAndLast</span><span class="p">([</span><span class="s1">&#39;hi&#39;</span><span class="p">,</span> <span class="s1">&#39;goodbye&#39;</span><span class="p">,</span> <span class="s1">&#39;smile&#39;</span><span class="p">])</span> <span class="c1">// [&#39;hi&#39;, &#39;ge&#39;, &#39;se&#39;]</span>
</pre></div>
</div>
</div>
<div class="section" id="addkeyandvalue">
<h3>addKeyAndValue</h3>
<p>Write a function called addKeyAndValue which accepts an array of objects, a key, and a value and returns the array passed to the function with the new key and value added for each object</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">addKeyAndValue</span><span class="p">(</span>
<span class="p">[</span>
  <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Matt&#39;</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">}</span>
<span class="p">],</span>
  <span class="s1">&#39;title&#39;</span><span class="p">,</span>
  <span class="s1">&#39;instructor&#39;</span>
<span class="p">)</span>

<span class="cm">/*</span>
<span class="cm">  [</span>
<span class="cm">    {name: &#39;Elie&#39;, title:&#39;instructor&#39;},</span>
<span class="cm">    {name: &#39;Tim&#39;, title:&#39;instructor&#39;},</span>
<span class="cm">    {name: &#39;Matt&#39;, title:&#39;instructor&#39;},</span>
<span class="cm">    {name: &#39;Colt&#39;, title:&#39;instructor&#39;}</span>
<span class="cm">  ]</span>
<span class="cm">*/</span>
</pre></div>
</div>
</div>
<div class="section" id="vowelcount">
<h3>vowelCount</h3>
<p>Write a function called vowelCount which accepts a string and returns an object with the keys as the vowel and the values as the number of times the vowel appears in the string. This function should be case insensitive so a lowercase letter and uppercase letter should count</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">vowelCount</span><span class="p">(</span><span class="s1">&#39;Elie&#39;</span><span class="p">)</span> <span class="c1">// {e:2,i:1};</span>
<span class="nx">vowelCount</span><span class="p">(</span><span class="s1">&#39;Tim&#39;</span><span class="p">)</span> <span class="c1">// {i:1};</span>
<span class="nx">vowelCount</span><span class="p">(</span><span class="s1">&#39;Matt&#39;</span><span class="p">)</span> <span class="c1">// {a:1})</span>
<span class="nx">vowelCount</span><span class="p">(</span><span class="s1">&#39;hmmm&#39;</span><span class="p">)</span> <span class="c1">// {};</span>
<span class="nx">vowelCount</span><span class="p">(</span><span class="s1">&#39;I Am awesome and so are you&#39;</span><span class="p">)</span> <span class="c1">// {i: 1, a: 4, e: 3, o: 3, u: 1}</span>
</pre></div>
</div>
</div>
</div>
<div class="section" id="map">
<h2>map</h2>
<div class="section" id="doublevalueswithmap">
<h3>doubleValuesWithMap</h3>
<p>Write a function called doubleValuesWithMap which accepts an array and returns a new array with all the values in the array passed to the function doubled</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">doubleValuesWithMap</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [2,4,6]</span>
<span class="nx">doubleValuesWithMap</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="o">-</span><span class="mi">2</span><span class="p">,</span><span class="o">-</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [2,-4,-6]</span>
</pre></div>
</div>
<p>function doubleValuesWithMap(arr) {}</p>
</div>
<div class="section" id="valtimesindex">
<h3>valTimesIndex</h3>
<p>Write a function called valTimesIndex which accepts an array and returns a new array with each value multiplied by the index it is currently at in the array.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">valTimesIndex</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [0,2,6]</span>
<span class="nx">valTimesIndex</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="o">-</span><span class="mi">2</span><span class="p">,</span><span class="o">-</span><span class="mi">3</span><span class="p">])</span> <span class="c1">// [0,-2,-6]</span>
</pre></div>
</div>
</div>
<div class="section" id="extractkey">
<h3>extractKey</h3>
<p>Write a function called extractKey which accepts an array of objects and some key and returns a new array with the value of that key in each object.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">extractKey</span><span class="p">(</span>
  <span class="p">[</span>
    <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Matt&#39;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">name</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">}</span>
  <span class="p">],</span>
  <span class="s1">&#39;name&#39;</span>
<span class="p">)</span>

  <span class="c1">// [&#39;Elie&#39;, &#39;Tim&#39;, Matt&#39;, &#39;Colt&#39;]</span>
</pre></div>
</div>
</div>
<div class="section" id="extractfullname">
<h3>extractFullName</h3>
<p>Write a function called extractFullName which accepts an array of objects and returns a new array with the value of the key with a name of “first” and the value of a key with the name of  “last” in each object, concatenated together with a space.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="cm">/*</span>
<span class="cm">extractFullName([</span>
<span class="cm">  {first: &#39;Elie&#39;, last:&quot;Schoppik&quot;},</span>
<span class="cm">  {first: &#39;Tim&#39;, last:&quot;Garcia&quot;},</span>
<span class="cm">  {first: &#39;Matt&#39;, last:&quot;Lane&quot;},</span>
<span class="cm">  {first: &#39;Colt&#39;, last:&quot;Steele&quot;}</span>
<span class="cm">])</span>

<span class="cm">  // [&#39;Elie Schoppik&#39;, &#39;Tim Garcia&#39;, &#39;Matt Lane&#39;, &#39;Colt Steele&#39;]</span>
<span class="cm">*/</span>
</pre></div>
</div>
</div>
</div>
<div class="section" id="filter">
<h2>filter</h2>
<div class="section" id="filterbyvalue">
<h3>filterByValue</h3>
<p>Write a function called filterByValue which accepts an array of objects and a key and returns a new array with all the objects that contain that key.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">filterByValue</span><span class="p">(</span>
<span class="p">[</span>
  <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Schoppik&quot;</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Garcia&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Matt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Lane&quot;</span><span class="p">},</span>
  <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Steele&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">}</span>
<span class="p">],</span>
<span class="s1">&#39;isCatOwner&#39;</span>
<span class="p">)</span>

<span class="cm">/*</span>
<span class="cm">  [</span>
<span class="cm">    {first: &#39;Tim&#39;, last:&quot;Garcia&quot;, isCatOwner: true},</span>
<span class="cm">    {first: &#39;Colt&#39;, last:&quot;Steele&quot;, isCatOwner: true}</span>
<span class="cm">  ]</span>
<span class="cm">*/</span>
</pre></div>
</div>
</div>
<div class="section" id="find">
<h3>find</h3>
<p>Write a function called find which accepts an array and a value and returns the first element in the array that has the same value as the second parameter or undefined if the value is not found in the array.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">find</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">],</span> <span class="mi">3</span><span class="p">)</span> <span class="c1">// 3</span>
<span class="nx">find</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">],</span> <span class="mi">10</span><span class="p">)</span> <span class="c1">// undefined</span>
</pre></div>
</div>
</div>
<div class="section" id="findinobj">
<h3>findInObj</h3>
<p>Write a function called findInObj which accepts an array of objects, a key, and some value to search for and returns the first found value in the array.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">findInObj</span><span class="p">(</span>
  <span class="p">[</span>
    <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Elie&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Schoppik&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Tim&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Garcia&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;att&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Lane&quot;</span><span class="p">},</span>
    <span class="p">{</span><span class="nx">first</span><span class="o">:</span> <span class="s1">&#39;Colt&#39;</span><span class="p">,</span> <span class="nx">last</span><span class="o">:</span><span class="s2">&quot;Steele&quot;</span><span class="p">,</span> <span class="nx">isCatOwner</span><span class="o">:</span> <span class="kc">true</span><span class="p">}</span>
  <span class="p">],</span>
  <span class="s1">&#39;isCatOwner&#39;</span><span class="p">,</span>
  <span class="kc">true</span>
<span class="p">)</span>

<span class="c1">// {first: &#39;Tim&#39;, last:&quot;Garcia&quot;, isCatOwner: true}</span>
</pre></div>
</div>
</div>
<div class="section" id="removevowels">
<h3>removeVowels</h3>
<p>Write a function called removeVowels which accepts a string and returns a new string with all of the vowels (both uppercased and lowercased) removed. Every character in the new string should be lowercased.</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">removeVowels</span><span class="p">(</span><span class="s1">&#39;Elie&#39;</span><span class="p">)</span> <span class="c1">// (&#39;l&#39;)</span>
<span class="nx">removeVowels</span><span class="p">(</span><span class="s1">&#39;TIM&#39;</span><span class="p">)</span> <span class="c1">// (&#39;tm&#39;)</span>
<span class="nx">removeVowels</span><span class="p">(</span><span class="s1">&#39;ZZZZZZ&#39;</span><span class="p">)</span> <span class="c1">// (&#39;zzzzzz&#39;)</span>
</pre></div>
</div>
</div>
<div class="section" id="doubleoddnumbers">
<h3>doubleOddNumbers</h3>
<p>Write a function called doubleOddNumbers which accepts an array and returns a new array with all of the odd numbers doubled (HINT - you can use map and fitler to double and then filter the odd numbers).</p>
<div class="highlight-js notranslate"><div class="highlight"><pre><span></span><span class="nx">doubleOddNumbers</span><span class="p">([</span><span class="mi">1</span><span class="p">,</span><span class="mi">2</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">5</span><span class="p">])</span> <span class="c1">// [2,6,10]</span>
<span class="nx">doubleOddNumbers</span><span class="p">([</span><span class="mi">4</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">4</span><span class="p">,</span><span class="mi">4</span><span class="p">])</span> <span class="c1">// []</span>
</pre></div>
</div>
</div>
</div>
