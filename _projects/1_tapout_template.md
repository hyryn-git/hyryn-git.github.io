---
layout: page
title: "[CHIP NAME] — [Technology Node]"
description: "[Brief one-line description of the tape-out project]"
img: assets/img/[your_chip_photo].png
importance: 1
category: tapeout
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid 
            loading="eager" 
            path="assets/img/[your_chip_photo].png" 
            title="[Chip title]" 
            class="img-fluid rounded z-depth-1" 
        %}
    </div>
</div>
<div class="caption">
    [Caption: Chip micrograph or layout of your design.]
</div>

## Overview

[Describe your tape-out project: what is this chip, what does it do, what technology was used.]

### Key Specifications

| Parameter | Value |
|-----------|-------|
| Technology | [e.g., 28nm CMOS, 40nm] |
| Area | [e.g., 2mm × 2mm] |
| Supply Voltage | [e.g., 1.0V] |
| Operating Frequency | [e.g., 200 MHz] |
| Power | [e.g., 50 mW] |
| Key Feature | [e.g., MRAM-based compute-in-memory] |

## Architecture

[Describe the chip architecture. Insert block diagram.]

{% include figure.liquid 
    path="assets/img/[your_block_diagram].png" 
    title="Block diagram" 
    class="img-fluid rounded z-depth-1" 
%}

## Measurement Results

[Describe measurement results. Insert measurement plots.]

## Links

- [Link to datasheet or paper]
- [Link to GitHub repository if applicable]
