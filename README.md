# [Go Lang Functions](https://golangfunc.com)

+ [Go Lang Functions on Github](https://golang-func.github.io/www/)


## Go versus Python 3 fastest programs

vs C# .NET
vs C++
vs Java
vs Python
vs Rust




<div>
    <p>Always look at the source code.
    </p><p>These are only the fastest programs. Do some of them use manually vectorized SIMD? Look at the <a href="../measurements/go.html"><span>other</span></a> <a href="../measurements/python3.html"><span>programs</span></a>. They may seem more-like a <em>fair</em> comparison to you.
  </p><h2></h2>
</div>
<table>
  <tbody>
  <tr>
    <th colspan="3"><a href="../performance/nbody.html"><span>n-body</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/nbody-go-3.html"><span>Go</span></a>
    </td><td class="best">6.38
    </td><td>1,896
    </td><td>1200
    </td><td>6.43
    </td><td class="message">0%&nbsp;100%&nbsp;1%&nbsp;0%
  </td></tr><tr>
    <td><a href="../program/nbody-python3-1.html"><span>Python&nbsp;3</span></a>
    </td><td>567.56
    </td><td>8,076
    </td><td>1196
    </td><td>570.95
    </td><td class="message">0%&nbsp;0%&nbsp;0%&nbsp;100%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/spectralnorm.html"><span>spectral-norm</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/spectralnorm-go-4.html"><span>Go</span></a>
    </td><td class="best">1.44
    </td><td>2,356
    </td><td>548
    </td><td>5.71
    </td><td class="message">99%&nbsp;99%&nbsp;99%&nbsp;99%
  </td></tr><tr>
    <td><a href="../program/spectralnorm-python3-8.html"><span>Python&nbsp;3</span></a>
    </td><td>120.99
    </td><td>13,424
    </td><td>407
    </td><td>479.86
    </td><td class="message">99%&nbsp;99%&nbsp;99%&nbsp;99%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/fannkuchredux.html"><span>fannkuch-redux</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/fannkuchredux-go-3.html"><span>Go</span></a>
    </td><td class="best">7.59
    </td><td>2,064
    </td><td>969
    </td><td>30.31
    </td><td class="message">100%&nbsp;100%&nbsp;100%&nbsp;100%
  </td></tr><tr>
    <td><a href="../program/fannkuchredux-python3-4.html"><span>Python&nbsp;3</span></a>
    </td><td>352.29
    </td><td>12,232
    </td><td>950
    </td><td>1,392.10
    </td><td class="message">97%&nbsp;99%&nbsp;100%&nbsp;99%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/mandelbrot.html"><span>mandelbrot</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/mandelbrot-go-3.html"><span>Go</span></a>
    </td><td class="best">3.75
    </td><td>34,832
    </td><td>894
    </td><td>14.92
    </td><td class="message">100%&nbsp;99%&nbsp;99%&nbsp;100%
  </td></tr><tr>
    <td><a href="../program/mandelbrot-python3-7.html"><span>Python&nbsp;3</span></a>
    </td><td>163.32
    </td><td>12,080
    </td><td>688
    </td><td>642.00
    </td><td class="message">98%&nbsp;98%&nbsp;98%&nbsp;98%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/fasta.html"><span>fasta</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/fasta-go-2.html"><span>Go</span></a>
    </td><td class="best">1.28
    </td><td>11,276
    </td><td>1404
    </td><td>3.78
    </td><td class="message">65%&nbsp;86%&nbsp;81%&nbsp;65%
  </td></tr><tr>
    <td><a href="../program/fasta-python3-5.html"><span>Python&nbsp;3</span></a>
    </td><td>37.32
    </td><td>846,264
    </td><td>1947
    </td><td>71.03
    </td><td class="message">10%&nbsp;67%&nbsp;83%&nbsp;30%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/knucleotide.html"><span>k-nucleotide</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/knucleotide-go-7.html"><span>Go</span></a>
    </td><td class="best">8.30
    </td><td>160,300
    </td><td>1607
    </td><td>31.96
    </td><td class="message">96%&nbsp;98%&nbsp;96%&nbsp;95%
  </td></tr><tr>
    <td><a href="../program/knucleotide-python3-3.html"><span>Python&nbsp;3</span></a>
    </td><td>46.28
    </td><td>241,108
    </td><td>1967
    </td><td>176.42
    </td><td class="message">94%&nbsp;97%&nbsp;95%&nbsp;96%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/revcomp.html"><span>reverse-complement</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/revcomp-go-6.html"><span>Go</span></a>
    </td><td class="best">1.42
    </td><td>1,344,600
    </td><td>1338
    </td><td>2.66
    </td><td class="message">57%&nbsp;36%&nbsp;71%&nbsp;24%
  </td></tr><tr>
    <td><a href="../program/revcomp-python3-6.html"><span>Python&nbsp;3</span></a>
    </td><td>7.20
    </td><td>1,005,184
    </td><td>814
    </td><td>10.75
    </td><td class="message">20%&nbsp;53%&nbsp;48%&nbsp;29%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/binarytrees.html"><span>binary-trees</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/binarytrees-go-8.html"><span>Go</span></a>
    </td><td class="best">12.80
    </td><td>385,036
    </td><td>1017
    </td><td>43.87
    </td><td class="message">85%&nbsp;87%&nbsp;85%&nbsp;86%
  </td></tr><tr>
    <td><a href="../program/binarytrees-python3-1.html"><span>Python&nbsp;3</span></a>
    </td><td>51.07
    </td><td>278,324
    </td><td>589
    </td><td>178.28
    </td><td class="message">85%&nbsp;86%&nbsp;93%&nbsp;85%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/pidigits.html"><span>pidigits</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/pidigits-go-4.html"><span>Go</span></a>
    </td><td class="best">1.00
    </td><td>8,952
    </td><td>683
    </td><td>1.04
    </td><td class="message">0%&nbsp;3%&nbsp;99%&nbsp;2%
  </td></tr><tr>
    <td><a href="../program/pidigits-python3-3.html"><span>Python&nbsp;3</span></a>
    </td><td>1.28
    </td><td>12,024
    </td><td>567
    </td><td>1.29
    </td><td class="message">0%&nbsp;1%&nbsp;100%&nbsp;0%
  </td></tr></tbody><tbody>
  <tr>
    <th colspan="3"><a href="../performance/regexredux.html"><span>regex-redux</span></a>
    </th><th colspan="3">
  </th></tr><tr>
    <th>source
    </th><th>secs
    </th><th>mem
    </th><th>gz
    </th><th>busy
    </th><th>cpu load
  </th></tr><tr>
    <td><a href="../program/regexredux-go-5.html"><span>Go</span></a>
    </td><td>3.94
    </td><td>323,252
    </td><td>810
    </td><td>6.14
    </td><td class="message">74%&nbsp;30%&nbsp;19%&nbsp;33%
  </td></tr><tr>
    <td><a href="../program/regexredux-python3-2.html"><span>Python&nbsp;3</span></a>
    </td><td>1.36
    </td><td>111,852
    </td><td>1403
    </td><td>2.64
    </td><td class="message">32%&nbsp;40%&nbsp;33%&nbsp;88%
  </td></tr></tbody><tbody>
  <tr>
    <td>Go
    </td><td colspan="5" class="message"><p>go version go1.16 linux/amd64

  </p></td></tr><tr>
    <td>Python&nbsp;3
    </td><td colspan="5" class="message"><p>Python 3.9.2

</p></td></tr></tbody></table>
<nav>
  <ul>
    <li><a href="../measurements/go.html"><span>all Go programs &amp; measurements</span></a>
    </li><li><a href="../measurements/python3.html"><span>all Python 3 programs &amp; measurements</span></a>
  </li></ul>
</nav>


---
+ [edit](https://github.com/golang-func/www/edit/main/README.md)
```
https://github.com/golang-func/www.git
```
