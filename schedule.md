---
layout: page
title: "Course Schedule"
permalink: /schedule.html
---

<style>
table.calendar {
    font-family: arial, helvetica;
    font-size: 10pt;
    empty-cells: show;
    border: 1px solid #000000;
    border-collapse: collapse;
}
table.calendar tr td {
    border: 1px solid #aaaaaa;
}
table.calendar tr {
    vertical-align: top;
    height: 5em;
    background: #ffffff;
}
table.calendar thead tr {
    text-align: center;
    background: #444444;
    color: #ffffff;
    height: auto;
    font-weight: bold;
}
/*.date {
	background: Gainsboro;
}*/
.holiday {
    background: #F0FFF0;
}
.lecture {
    background: #ffffaa;
}
.cpuvirt {
    background: Moccasin;
}
.memvirt {
    background: LightGreen;
}
.concurrency {
    background: PaleTurquoise;
}
.persistence {
    background: Plum;
}
.distsys {
    background: Aqua;
}
.distsys {
    background: Gold;
}
.virt {
    background: Khaki;
}
.presentation {
    background: LemonChiffon;
}
.exam {
    background: DarkOrange;
}
.important {
    background: Pink;
}
.nodue {
    background: #FFFAFA;
}
.optional {
    background: Linen;
}
.reading {
    color: Black;
}
.deadline {
    background: #ffaaaa;
}
.hwdue {
    color: #ff0000;
	font-weight: bold;
}
.assignment {
    color: #0aa00a;
	font-weight: bold;
}
.date {
	background: #eeeeee;
    color: #444444;
}
</style>

The course schedule and the <a href="./reading_list.html">reading list</a> are tentative and subject to change\*.

<p>
<table class="calendar" cellspacing="0" cellpadding="6" width="100%">
 <thead>
  <tr>
   <td width="10%">Week</td><td width="60%">Wednesday</td>
   <td width="30%">Friday</td>
  </tr>
 </thead>

<!--tr--> <!-- week of Jan 20 -->
  <!--td id="2020-1-20" class="date"><b>Week 1</b></td>
  <td class="holiday">Jan 27<br/>
	<b>MLK Day</b> (NO CLASS)</td>
  <td class="nodue">Jan 23</td>
</tr-->
<tr> <!-- week of Jan 26 -->
  <td id="2021-1-26" class="date"><b>Week 1</b></td>
  <td class="cpuvirt">Jan 26<br/>
	<b>Lec 1:</b> Introduction, CPU scheduling (fundamental)
  </td>
  <td class="nodue">Jan 28<br/>
	Take prerequisite <a target="_blank" href="https://docs.google.com/document/d/1NRL5eLQ-KqhZ6f1PSk-vAbaE9y7FKVnD-aXTCUfBlH8/edit?usp=sharing">quiz</a> <br/>
	Fill out <a target="_blank" href="https://forms.gle/mDEHgcg5iwL1Ty1v8">background survey</a> <br/>
	<span class="assignment">Pick project idea</span></td>
  </td>
</tr>
<tr> <!-- week of Feb 2 -->
  <td id="2021-2-2" class="date"><b>Week 2</b></td>
  <td class="cpuvirt">Feb 2<br/>
	Advanced scheduling: CFS, ghOSt
	</td>
  <td class="deadline">Feb 4<br/>
	<span class="hwdue">Form a team with an idea</span></td>
</tr>
<tr> <!-- week of Feb 9 -->
  <td id="2021-2-9" class="date"><b>Week 3</b></td>
  <td class="memvirt">Feb 9<br/>
	Memory virtualization (fundamental)
	</td>
  <td class="nodue">Feb 11</td>
</tr>
<tr> <!-- week of Feb 16 -->
  <td id="2021-2-16" class="date"><b>Week 4</b></td>
  <td class="memvirt">Feb 16<br/>
	Memory virtualization (advanced)
	</td>
  <td class="deadline">Feb 18<br/>
	<span class="hwdue">Lab 2 due</span></td>
</tr>
<tr> <!-- week of Feb 23 -->
  <td id="2021-2-23" class="date"><b>Week 5</b></td>
  <td class="concurrency">Feb 23<br/>
	Concurrency (fundamental)
	</td>
  <td class="deadline">Feb 25 <br/>
	<span class="hwdue">Project proposal due</span>
  </td>
</tr>
<tr> <!-- week of Mar 2 -->
  <td id="2021-3-2" class="date"><b>Week 6</b></td>
  <td class="concurrency">Mar 2<br/>
	Concurrency (advanced)
  </td>
  <td class="nodue">Mar 4</td>
</tr>
<tr> <!-- week of Mar 9 -->
  <td id="2021-3-9" class="date"><b>Week 7</b></td>
  <td class="persistence">Mar 9<br/>
	File systems (fundamental)
  </td>
  <td class="nodue">Mar 11</td>
</tr>
<tr> <!-- week of Mar 16 -->
  <td id="2021-3-16" class="date"><b>Week 8</b></td>
  <td class="holiday">Mar 16<br/>
	Spring recess
	</td>
  <td class="nodue">Mar 18<br/>
  </td>
</tr>
<tr> <!-- week of Mar 23 -->
  <td id="2021-3-23" class="date"><b>Week 9</b></td>
  <td class="persistence">Mar 23<br/>
	Amazon Dynamo
  </td>
  <td class="deadline">Mar 25<br/>
	<span class="hwdue">Project checkpoint 1 due</span><br/>
</tr>
<tr> <!-- week of Mar 30 -->
  <td id="2021-3-30" class="date"><b>Week 10</b></td>
  <td class="persistence">Mar 30<br/>
	InfiniCache
	</td>
  <td class="nodue">Apr 1</td>
</tr>
<tr> <!-- week of Apr 6 -->
  <td id="2021-4-6" class="date"><b>Week 11</b></td>
  <td class="virt">Apr 6<br/>
	Xen
	</td>
  <td class="nodue">Apr 8</td>
</tr>
<tr> <!-- week of Apr 13 -->
  <td id="2021-4-13" class="date"><b>Week 12</b></td>
  <td class="virt">Apr 13<br/>
	AWS Firecracker
	</td>
  <td class="deadline">Apr 15<br/>
	<span class="hwdue">Project checkpoint 2 due</span><br/>
</tr>
<tr> <!-- week of Apr 20 -->
  <td id="2021-4-20" class="date"><b>Week 13</b></td>
  <td class="distsys">Apr 20<br/>
	MapReduce/GFS
	</td>
  <td class="nodue">Apr 22</td>
</tr>
<tr> <!-- week of Apr 27 -->
  <td id="2021-4-27" class="date"><b>Week 14</b></td>
  <td class="distsys">Apr 27<br/>
	Spark?
	</td>
  <td class="nodue">Apr 29</td>
</tr>
<tr> <!-- week of May 4 -->
  <td id="2021-5-4" class="date"><b>Week 15</b></td>
  <td class="presentation">May 5<br/>
	Wrap-up: Final project demo
	 </td>
  <td class="nodue">May 7</td>
</tr>
<tr> <!-- week of May 11 -->
  <td id="2021-5-11" class="date"><b>Week 16</b></td>
  <td class="presentation">May 11<br/>
	 TBD
	 </td>
  <td class="deadline">May 13<br/>
	<span class="hwdue">Project everything due</span><br/>
	</td>
</tr>

</table>

</p>

<p style='font-size:12pt'>&#42;: Color codings:
<table style='font-size:12pt'>
<tr> 
	<td align="center" class="cpuvirt"> -CPU Virtualization- </td>
	<td align="center" class="memvirt"> -Memory Virtualization- </td>
	<td align="center" class="concurrency"> -Concurrency- </td>
	<td align="center" class="persistence"> -Persistence- </td>
	<td align="center" class="virt"> -VMs/Containers- </td>
	<td align="center" class="distsys"> -Distributed Systems- </td>
</tr>
</table>
