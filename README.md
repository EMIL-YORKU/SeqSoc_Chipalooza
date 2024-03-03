# SeqSoc_Chipalooza

<p align="center">
<img src="./img/yorku.png" width ="800"/>
<br>
<br>
</p>
<p align="center">
<b> SKY130 CMOS Readout Array Design for Scalable Nanopore-Based DNA Sequencing
<br>
<br>
 <br>
<p align="center">
Authors:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sepideh Asgari <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Amirhossein&nbsp; Mohammadpanah<br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;Supervisor:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Prof. Sebastian Magierowski<br>
<br>
 <br>
 <p align="center">
 February 2024

Table of contents
==============================
<!--ts-->
  * [Motivation](#Motivation)
  * [Description](#Description)
  * [Design Goals](#Design-Goals)
  * [References](#References)
<!--te-->

Motivation
=======

Nanopore sequencing involves the use of nanopores, which can be biological or solid-state,
to determine the order of nucleotides in DNA by electrically measuring the movement of the
DNA through the nanopore. Nanopores are tiny apertures at the nanometer scale, directing
molecules to precise spatial locations. Electrically, nanopores function as voltage-clamp sen-
sors, with a constant voltage applied across them to establish an ionic current. As illustrated in
Fig. 1, DNA is threaded through the nanopore during sequencing, causing modulation of the
ionic current in a complex relationship to the sequence of base molecules (A, C, G, T) in the
DNA strand.
<p align="center">
  <img src=/figures/dnasns.png alt="dnasns"/>
</p>
<h4 align="center">Figure 1. A block diagram of the Nanopore Sensor, Analog and Digital Components.</h4>
