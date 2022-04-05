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

Please enter the composition of your team by
filling this <a href="https://forms.gle/8EzAp7QNcZ8XeVmV6">Google Form</a>.
It's preferred that a team has 2 people. If you choose to work as
a team, only one team member needs to fill the form.

<p>
<table class="calendar" cellspacing="0" cellpadding="6" width="100%">
 <thead>
  <tr>
   <td width="10%">Week</td><td width="55%">Wednesday</td>
   <td width="35%">Friday</td>
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
  <td class="presentation">Jan 26<br/>
	<b>Lec 1:</b> Introduction [<a href="./public/lecs/lec1-intro.pdf">slides</a>]
  </td>
  <td class="nodue">Jan 28<br/>
	Take prerequisite <a target="_blank" href="https://docs.google.com/document/d/1NRL5eLQ-KqhZ6f1PSk-vAbaE9y7FKVnD-aXTCUfBlH8/edit?usp=sharing">quiz</a> <br/>
	Fill out <a target="_blank" href="https://forms.gle/mDEHgcg5iwL1Ty1v8">background survey</a> <br/>
	<span class="assignment">Project list released: Pick your idea+form a team</span>
  </td>
</tr>
<tr> <!-- week of Feb 2 -->
  <td id="2021-2-2" class="date"><b>Week 2</b></td>
  <td class="cpuvirt">Feb 2<br/>
	<b>Lec 2:</b> Basic scheduling [<a href="./public/lecs/lec2-basic-sched.pdf">slides</a>] [<a href="./public/lecs/lec2-basic-sched+notes.pdf">slides+notes</a>] <br/>
    <b>Reading:</b> <a href="http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-mechanisms.pdf">LDE</a> and <a href="http://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/cpu-sched.pdf">Scheduling (intro)</a>
	</td>
  <td class="deadline">Feb 4<br/>
	<span class="hwdue">Form a team due</span></td>
</tr>
<tr> <!-- week of Feb 9 -->
  <td id="2021-2-9" class="date"><b>Week 3</b></td>
  <td class="cpuvirt">Feb 9<br/>
	<b>Lec 3:</b> Advanced scheduling [<a href="./public/lecs/lec3-advanced-sched.pdf">slides</a>] [<a href="./public/lecs/lec3-advanced-sched+notes.pdf">slides+notes</a>] <br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/cpu-sched-mlfq.pdf">MLFQ</a>, <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-multi.pdf">Multi-core Sched (Linux)</a>, <a href="https://man7.org/linux/man-pages/man7/sched.7.html">man 7 sched</a>, and <a href="https://www.kernel.org/doc/html/latest/scheduler/sched-design-CFS.html">Linux CFS</a>
  </td>
  <td class="deadline">Feb 11<br/>
	<span class="hwdue">Pick a project idea due</span>
  </td>
</tr>
<tr> <!-- week of Feb 16 -->
  <td id="2021-2-16" class="date"><b>Week 4</b></td>
  <td class="memvirt">Feb 16<br/>
	<b>Lec 4:</b> Memory virtualization (fundamental) [<a href="./public/lecs/lec4-vm.pdf">slides</a>] [<a href="./public/lecs/lec4-vm+notes.pdf">slides+notes</a>] <br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-intro.pdf">Address spaces</a>, <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-mechanism.pdf">Address translation</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-paging.pdf">Paging</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-tlbs.pdf">TLB</a>,
	and <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-smalltables.pdf">Adv. PTs</a> <br/>
	<b>Optional:</b> <a href="https://meltdownattack.com/meltdown.pdf">Meltdown attack paper</a>, <a href="https://cacm.acm.org/magazines/2020/6/245161-meltdown/fulltext">CACM article</a>
  </td>
  <td class="nodue">Feb 18</td>
</tr>
<tr> <!-- week of Feb 23 -->
  <td id="2021-2-23" class="date"><b>Week 5</b></td>
  <td class="memvirt">Feb 23<br/>
	<b>Lec 4 (cont.):</b> Memory virtualization (fundamental)
  </td>
  <td class="deadline">Feb 25 <br/>
	<span class="hwdue">Project proposal due</span>
  </td>
</tr>
<tr> <!-- week of Mar 2 -->
  <td id="2021-3-2" class="date"><b>Week 6</b></td>
  <td class="memvirt">Mar 2<br/>
	<b>Lec 5:</b> Memory virtualization (advanced) [<a href="./public/lecs/lec5-vm-caching.pdf">slides</a>] [<a href="./public/lecs/lec5-vm-caching+notes.pdf">slides+notes</a>] <br/>
	<b>Reading:</b> Beyond physical memory: <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/vm-beyondphys.pdf">Mechanisms</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys-policy.pdf">(Caching) Policy</a>
  </td>
  <td class="nodue">Mar 4</td>
</tr>
<tr> <!-- week of Mar 9 -->
  <td id="2021-3-9" class="date"><b>Week 7</b></td>
  <td class="concurrency">Mar 9<br/>
	Mini exam 1 (7:20pm - 7:50pm) <br/>
	<b>Lec 6:</b> Concurrency I [<a href="./public/lecs/lec6-concurrency.pdf">slides</a>] [<a href="./public/lecs/lec6-concurrency+notes.pdf">slides+notes</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-api.pdf">Threads</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf">Concurrency intro</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf">Locks</a>, and
	<a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf">Semaphores</a>
  </td>
  <td class="nodue">Mar 11</td>
</tr>
<tr> <!-- week of Mar 16 -->
  <td id="2021-3-16" class="date"><b>Week 8</b></td>
  <td class="holiday">Mar 16<br/>
	Spring recess
	</td>
  <td class="nodue">Mar 18</td>
</tr>
<tr> <!-- week of Mar 23 -->
  <td id="2021-3-23" class="date"><b>Week 9</b></td>
  <td class="concurrency">Mar 23<br/>
	<b>Lec 7:</b> Concurrency II [<a href="./public/lecs/lec7-concurrency-cv.pdf">slides</a>] [<a href="./public/lecs/lec7-concurrency-cv+notes.pdf">slides+notes</a>]<br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-cv.pdf">CV</a>, <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf">Deadlocks</a>
  </td>
  <td class="deadline">Mar 25<br/>
	<span class="hwdue">Project checkpoint 1 due</span><br/>
  </td>
</tr>
<tr> <!-- week of Mar 30 -->
  <td id="2021-3-30" class="date"><b>Week 10</b></td>
  <td class="persistence">Mar 30<br/>
	<b>Lec 8:</b> Persistence (fundamental): HDD, SSD, FS abstraction [<a href="./public/lecs/lec8-persistence-hdd-ssd-fs.pdf">slides</a>] [<a href="./public/lecs/lec8-persistence-hdd-ssd-fs.pptx">pptx+notes</a>] <br/>
	<b>Reading:</b> <a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-disks.pdf">HDDs</a>,
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-ssd.pdf">SSDs</a>, and 
	<a href="https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2016/Book/file-intro.pdf">File system intro</a>
  </td>
  <td class="nodue">Apr 1</td>
</tr>
<tr> <!-- week of Apr 6 -->
  <td id="2021-4-6" class="date"><b>Week 11</b></td>
  <td class="persistence">Apr 6<br/>
	<b>Lec 9:</b> Persistence (advanced): FS impl, RAID, InfiniCache
  </td>
  <td class="nodue">Apr 8</td>
</tr>
<tr> <!-- week of Apr 13 -->
  <td id="2021-4-13" class="date"><b>Week 12</b></td>
  <td class="virt">Apr 13<br/>
	<b>Lec 10:</b> Virtualization (VM, container)
	</td>
  <td class="deadline">Apr 15<br/>
	<span class="hwdue">Project checkpoint 2 due</span><br/>
  </td>
</tr>
<tr> <!-- week of Apr 20 -->
  <td id="2021-4-20" class="date"><b>Week 13</b></td>
  <td class="distsys">Apr 20<br/>
	<b>Lec 11:</b> MapReduce, GFS
	</td>
  <td class="nodue">Apr 22</td>
</tr>
<tr> <!-- week of Apr 27 -->
  <td id="2021-4-27" class="date"><b>Week 14</b></td>
  <td class="distsys">Apr 27<br/>
	<b>Lec 12:</b> Spark
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
  <td class="deadline">May 11<br/>
	<span class="hwdue">Project everything due</span><br/>
	</td>
  <td class="nodue">May 13
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
