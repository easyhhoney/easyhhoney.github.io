---
layout: post
title:  "1_ Cellular Homeostasis and Membrane Potential (2)"
date: 2024-10-08 18:00:00 +09:00
categories: bioelectric
---
#### Contents 
 1. Osmotic Balance (삼투압)
 2. Equilibrium Potential (평형 전위)



* * *
## 1. 삼투압 (Osmotic Balance)

<img src="{{ site.baseurl }}/images/스크린샷 2024-10-11 오후 5.43.20.png" alt="삼투압2" width="750" height="500">
<strong>삼투압 (Osmotic Balance)</strong> <br>

위 그림처럼, 농도가 다르고, 부피가 같은 물질이 있을 경우를 가정해보자. <br>
-  이때 <span class="highlight-green"> 물과 용질이 막 사이를 넘나들 수 있는 경우 </span>라고 해보자. <br>
부피는 같지만 농도가 다르므로 용질이 농도가 높은 쪽에서 낮은 쪽으로 농도가 서로 같아질 때까지 이동할 것이다. <br>
따라서 농도는 150mM, 150mM, 부피는 1L, 1L로 부피와 농도 모두 같아질 것이다. <br>
- 용질은 움직이지 못하고 <span class="highlight-green"> 물만 막 사이를 넘나들 수 있는 경우</span>에는 어떻게 될까? <br>
이때도 마찬가지로 같은 농도를 유지하기 위해 물이 이동할 것이다.  <br>
따라서 물은 높은 농도에서 낮은 농도로 이동할 것이므로, 농도는 150mM, 150mM로 같고 부피는 2/3L, 4/3L가 될 것이다. <br>
결국 평형을 이루려는 성질로 인해 용질이나 용액이 이동한다.<br>

<div style="display: flex; justify-content: space-between;">
  <img src="{{ site.baseurl }}/images/스크린샷 2024-10-11 오후 2.47.45.png" alt="삼투압3" width="550" height="200">
  <img src="{{ site.baseurl }}/images/스크린샷 2024-10-11 오후 2.47.55.png" alt="삼투압4" width="300" height="150">
</div>

<span class="highlight-green">Hypertonic</span> : 세포 내부보다 외부가 농도가 높은 경우, 물은 농도가 낮은 세포 내에서 세포 외부로 이동한다.<br>
이 경우에 세포 안에서 물을 무한히 빼야 하기 때문에 세포는 결국 죽게 된다.<br>
<span class="highlight-green">Hypotonic</span> : 두번째 그림처럼 세푸 내부가 외부보다 농도가 높은 경우에는 물을 무한히 세포 안으로 물이 무한히 들어가야 농도 균형이 맞춰진다. 결국에는 세포가 쪼그라들어 죽고 마는 것이다 <br>

결국 물뿐만 아니라 다른 융질이나 용매가 이동해야 세포가 팽창하거나 수축하지 않으면서 평형을 유지할 수 있다.<br>

<br>

<p class="message">
   <span class="highlight-lemon">Exercise A.</span> 이온이 막을 통과하지 못하는 경우<br>
  For the following case, determine the final equilibrium, cell volume given the starting conditions and an initial cell volume V<sub>0</sub>. <br>
</p>

<img src="{{ site.baseurl }}/images/스크린샷 2024-10-11 오후 5.54.06.png" alt="삼투압4" width="200" height="250" style = "float:left;">
(a) 세포 내부와 외부 농도가 모두 같기 때문에, 부피 변화가 일어나지 않는다. <br>
E<sub>final</sub> = 100mM <br>
V<sub>final</sub> = V<sub>0</sub> <br>
(b) 세포 내부가 외부보다 농도가 높기 때문에, 세포 외부에서 세포 내부로 물이 들어온다. <br>
세포 외부는 물이 아무리 빠져나가도 농도는 변하지 않기 때문에, 세포 외부의 농도가 될 때까지 세포 내부에 물이 들어온다.<br>
E<sub>final</sub> = 100mM <br>
V<sub>final</sub> = 2V<sub>0</sub> <br>


<p class="message">
   <span class="highlight-lemon">Exercise B.</span> Conservation of Charge : principle of electrical neutrality<br>
   determine a, b and c
 <br>
</p>

<img src="{{ site.baseurl }}/images/스크린샷 2024-10-13 오후 7.12.20.png" alt="삼투압5" width="300" height="150" style = "float:left;">

이온이 고려될 때, charge neutrality가 고려되어야 한다. <br>
Na<sup>+</sup>가 갇혀있고, Cl<sup>-</sup>만이 세포막을 통과할 수 있을 때, positive charge와 negative charge가 반드시 균형이 맞아야 한다. <br>

1) <span class="highlight-green">Electrical charge neutrality</span> <br>
50mM - a = 0      -> a = 50mM <br>
b - c = 0         -> b = c <br>
내부에서의 charge의 합은 0이 되어야한다.<br>
즉, 세포 내부에서 양전하의 합과 음전하의 합은 같아야 한다. <br>

2) <span class="highlight-green"> Concentration balance</span> <br>
50 + a +100 = b + c<br>
200 = b + c<br>
200 = 2b = 2c<br>
b = c = 100<br>
세포 내부의 농도와 세포 외부 농도는 같아야 한다. <br>

a = 50mM, b = 100mM, c = 100mM <br>
<br>

## 2. Equilibrium Potential

용어 : 농도 평형 [Diffusion], 전기장 [Drift] <br>

이온은 농도 기울기 (concentration gradient)를 따라 확산되어 세포막을 통과한다.<br>
세포막 양측에는 전하의 차이가 존재하여 전기장이 형성된다.<br>
Concentration gradient와 Electrical potential difference는 이온의 이동을 결정하는 상호작용이다.<br>
이 둘이 균형을 이루는 상태를 평형 상태라고 하고, 이때 이온의 이동은 더 이상 일어나지 않는다.<br>

<strong> Nernst Equation for equilibrium potential </strong> <br>

<img src="{{ site.baseurl }}/images/스크린샷 2024-10-13 오후 8.40.56.png" alt="삼투압6" width="310" height="80">

Nernst Equation은 세포막을 통해 특정 이온의 확산을 하지 않도록 하는 세포막 양측의 전위를 계산하는 방정식이다. Nernst 전위의 크기는 세포막 안팎의 해당 이온의 농도 비율에 의해 결정된다.<br>

R : 기체 상수 (8.314 J/mol·K)<br>
T : 절대 온도 (Kelvin)<br>
F : Faraday 상수 (96,485 C/mol)<br>

25℃를 전제로 하여 상수를 대입하고, 상용로그 값을 사용하여 (lnx = 2.303logx) 방정식을 간편하게 만들어 아래 식이 완성된다.

<img src="{{ site.baseurl }}/images/스크린샷 2024-10-13 오후 8.42.56.png" alt="삼투압6" width="270" height="80">
<br>
## 3. Donnan Equilibrium

도난 평형 (Donnan equilibrium) : 두 개의 이온이 세포막을 통과할 수 있을 때, 세포 내부와 외부의 이온 농도 비율을 결정하는 원리이다. 반투막을 통해 물은 자유롭게 이동할 수 있지만 한가지 이온은 이동할 수 없는 상황에서 적용된다.

예를 들어, K<sup>+</sup> Cl<sup>+</sup> 이온이 세포막을 통과할 수 있다고 가정해보자. <br>
세포 안에서 오직 하나의 membrane potential이 있을 수 있다. <br>


<img src="{{ site.baseurl }}/images/스크린샷 2024-10-13 오후 9.04.39.png" alt="삼투압6" width="550" height="80">

  <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
  <script>
    MathJax.typeset();
  </script>

위 식을 정리하면,

$$\frac{[K^+]_{out}}{[K^+]_{in}} = \frac{[Cl^-]_{in}}{[Cl^-]_{out}}$$

결국  K<sup>+</sup>와 Cl<sup>-</sup> 이온 내부의 농도 곱 =  K<sup>+</sup> Cl<sup>-</sup> 이온 외부의 농도의 곱과 같다.