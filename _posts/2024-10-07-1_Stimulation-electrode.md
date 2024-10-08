---
layout: post
title:  "Stimulation Electrode - Charge Balance"
date: 2024-10-07 18:00:00 +09:00
categories: electrode
---

## Contents 
   1. Cathodal Protect
   2. Electrical Threshold
   3. 크기에 따른 Neural Stimulation Electrode


<p class="message">
Charge Balance란? <br>
즉 전하의 균형을 맞추는 것 <br>
양이온의 전체 전하의 합 = 음이온의 전체 전하의 합 <br>
</p>

* * *

## 1. Cathodal Protect
  
   **정의**<br>
   Charge Balance를 유지하기 위해, neural stimulation에서 사용하는 전류의 파형. <br>
   Stimulatior가 Electrode에 전극을 가할 때, 특정 시점에서 일정 charge를 유지하면서 전류를 흐르도록 하는 것 <br>

   **목적**<br>
   1.산화 환원을 유도하지 않는 범위 내에서 electrode potential을 유지하기 위함. <br>
   2.stimulation pulse에 전달될 수도 있는 charge를 제한하기 위함. <br>
 
   **중요성**<br>
   Charge Balance가 유지되지 않을 경우, 주변 조직에 손상을 입히거나 전극이 부식될 가능성이 있음 <br>
   따라서 Electrode Stimulation 시 이를 고려하면서 자극을 가해야 함.

   **한계**<br>
   Charge-balanced이라도 조직이나 전극 손상을 입히는 비가역적인 산화환원 반응이 일어나는 시점에 <br>
   pulse delivery동안 전극이 polarized될 수 있음. <br>
   따라서 stimulus waveform은 전류와 charge densities를 고려해야 함 <br>


### Cathodal Protect Waveform

   <img src="{{ site.baseurl }}/images/image.png" alt="Cathodal Image" width="800" height="400">
   결국 Charge Balance하도록 Stimulation Waveform을 전달한다는 것 <br>
   = 위 그림 Waveform의 면적을 같게 하도록 하는 일정 Charge를 전극에 전달하는 것

   * **Leading phase** <br>
      leading phase를 cathodal하게 혹은 anodal하게 설정하는 것은 사용자의 정의에 따라 다름. <br>
      보통은 leading phase를 cathodal하게 설정하지만,<br>
      anodal할 경우 몇몇 neural elements를 더 효율적으로 활성화시킬 수 있다는 reference가 있음 <br>

   * **GSA (geometric surface area)** <br>
      charge와 current densities를 정의하는데 사용됨<br>

<br>
<br>

## 2. Electrical Threshold

   <img src="{{ site.baseurl }}/images/image_2.jpeg" alt="Charge/Phase Image width" width="1000" height="500">
   현재 신경 보철에서 요구되는 Chage/phase와 charge density 제한 범위


* * *
