---
layout: default
title: "Welcome"
lang: en
---

# Welcome to EmbedLinuxAcademy

Explore tutorials on **C**, **C++**, **Embedded Linux**, **Yocto**, and **Kernel Driver Development**.

## Tutorials

<!-- Accordion Menu -->
<div class="accordion">
  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(this)">
      Introduction to Yocto Build
    </button>
    <div class="accordion-content">
      <p>This section covers the basics of getting started with EmbedLinuxAcademy.</p>
    </div>
  </div>

  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(this)">
      Section 2: Advanced Topics
    </button>
    <div class="accordion-content">
      <p>Advanced topics in Embedded Linux and Kernel Driver Development.</p>
    </div>
  </div>

  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(this)">
      Section 3: Yocto Builds
    </button>
    <div class="accordion-content">
      <p>Learn about Yocto Builds and how to customize them for your project.</p>
    </div>
  </div>
</div>


<script>
  function toggleAccordion(element) {
    element.classList.toggle("active");
    var content = element.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  }
</script>


- Introduction to Yocto Build
- [Basics of C++ for Embedded Systems](tutorials/cpp-basics)
- [Kernel Driver Development 101](tutorials/kernel-driver-intro)

## About Us

EmbedLinuxAcademy provides in-depth tutorials and resources for developers focused on embedded systems and Linux kernel development.
