+++

title = "Towards Collective Operating Systems through Aggregate Computing"
description = "Presentation for the 2024 Flash Talk Challenge"
outputs = ["Reveal"]

+++

{{< slide background-image="./images/first-page.pdf">}}

<!-- ---

# Title

[**Angela Cortecchia**](mailto:angela.cortecchia@unibo.it)

<div style="text-align: center; width: 100%;">
<img src="example-background.svg" style="width: 40%" />
</div> -->
---

{{< slide background-image="./images/crowd.png" background-opacity="0.55">}}

<iframe width="100%" height="1000" loading="eager" frameborder="0" autoplay="true" src="./images/seoul.mp4"></iframe>
<small>Source: Youtube</small>

--- 

{{< slide background-image="./images/smartcity.webp" background-opacity="0.55">}}

{{< rectdiv >}}

# Application scenario:<br><em>Crowd management</em>

<div class="fragment">

Lot of **heterogeneous sensors** and **devices** employed.

- *Detect* crowd;
- *Steer* the crowd *to prevent* hazardous situation;
- Law enforcement can *intervene*.
</div>

{{< /rectdiv >}}

---

{{< slide background-image="./images/wearables.jpg" background-opacity="0.55">}}

{{< rectdiv >}}
# Challenges

Common approaches usually consist of _programming each single device_.

**Non-scalable** when thousands of different devices are involved.

<div class="fragment">

- *Different* way to implement *programs on different devices*;
- Some devices do *not support all functionalities*;
- *Time expensive* to program each single device;
- Devices have a *limited vision of the system*;
- *Non-friendly programming* for the developer.
</div>

<!-- - Not all devices support the same functionalities; -->
{{< /rectdiv >}}

---

{{< slide background-image="./images/question.svg" background-opacity="0.55">}}

{{< rectdiv >}}
# A possible solution?
{{< /rectdiv >}}

---

{{< slide background-image="./images/world.svg" background-opacity="0.55">}}


{{< rectdiv >}}

# Meet Aggregate Computing

A programming paradigm to **define the behavior of a collective of heterogeneous devices**.

Every device runs the same program and *adapts to dynamic changes in the environment*.

<div class="fragment">

### Current limitations:

- Aggregate systems **run just one program**;
- *Can not* be modified, added, or interrupted *at runtime without affecting other devices*,

limiting the usage scenarios.
</div>

{{< /rectdiv >}}

---

{{< slide background-image="./images/smartstation.png" background-opacity="0.55">}}

{{< rectdiv style="max-width: 80%;" >}}

# What do we need?

{{% multicol %}}

{{% col %}}
### Crowd Management scenario

<ul>
    <li class="fragment" data-fragment-index=0>Drones and sensors <em>observe and send data</em> to the system;</li>
    <li class="fragment" data-fragment-index=1>Crowd <em>steering based on data</em> evaluation;</li>
    <li class="fragment" data-fragment-index=2><em>Coordination</em> between devices;</li>
    <li class="fragment" data-fragment-index=3>Law enforcement <em>intervention</em>;</li>
</ul>
{{% /col %}}

{{% col %}}
### Effective technologies

<ul>
    <li class="fragment" data-fragment-index=0><em>Distributed</em> sensors and actuators able to <em>execute multiple programs</em>;</li>
    <li class="fragment" data-fragment-index=1>Communication between <em>different processes</em>;</li>
    <li class="fragment" data-fragment-index=2><em>Intra-process</em> communication;</li>
    <li class="fragment" data-fragment-index=3>Third-party entities able to <em>interrupt, pause, or add processes at runtime</em>.</li>
    <!-- <li>Interoperability between different devices.</li> -->
</ul>

{{% /col %}}

{{% /multicol %}}

{{< /rectdiv >}}

---

{{< slide background-image="./images/collective.svg" background-opacity="0.55">}}

{{< rectdiv >}}

# Idea: *Collective* Operating Systems

Aim to *parallel the main functionalities of modern OSs*,
from a **collective** point of view:

<!-- Closing the gap of the current technologies: -->

- Runtime program injection;
- Users and permissions;
- Signal and interrupts;
- Multiple processes able to communicate;
- Distributed sensors and actuators.
<!-- - Intra-process communication; -->

{{< /rectdiv >}}

---

## Thank you!
# :)
