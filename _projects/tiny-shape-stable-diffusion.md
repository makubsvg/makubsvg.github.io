---
title: Tiny Shape Stable Diffusion
description: A pytorch stable diffusion model to generate shapes.
date: 2026-11-23
image: /assets/img/2026-11-23-tiny-shape-stable-diffusion.png
---

A stable diffusion model using a classical approach with a u-net for denoising.
It generates positioned and sized circles or squares.
Indeed, the u-net is modified with a standard cross attention block that gives these parameters to the model.