---
layout: page
title: Project Proposals
permalink: /project-proposal/
---

We love new projects!

If you have an idea that you think would be amazing, submit the form below to tell us about it!

<button id="openFormButton">Submit Project Proposal</button>

<div id="formModal">
  <div id="modalContent">
    <span id="closeFormButton">&times;</span>
    <iframe
      id="formIframe"
      src="https://docs.google.com/forms/d/e/1FAIpQLSeZmX_rSOAq6P66FPpIGjhCkqWYotObgsK0_yePYnvriWOCYQ/viewform"
      title="Submit Project Proposal"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen
    ></iframe>
  </div>
</div>

[//]: # (TODO: fix console errors)

### What to Expect

Great planning is the key to any great project, and we want every project to be set up for success!

Every project evaluation will look a little different. Some may be rough ideas, while others are nearly completely planned out. 

__We're good with either!__

#### Project Evaluation/Planning Phase
* __Step 1__: Submit a proposal
* __Step 2__: We'll review it for alignment with the group's goals and capabilities, and decide whether to move forward.
* __Step 3__: We'll want to know more details about the project, what work has been done already, if stakeholders are engaged, what plans are in place for making it accessible, equitable,  tracking, maintaining, etc. If you don't have all the answers, that's ok! We can help you work through getting them.
* __Step 4__: Once we have the information we need, we'll work together to create an initial, high-level project plan.
* __Step 5__: The moment is here! Now we'll present the project to the broader group, and get volunteers who are interested in working on it!

#### Project Execution Phase

Let's do the thing, and make this idea a reality!

### Additional Forms

If we decide to move forward with the project, we will have you fill out these forms, or work with you on filling them out as needed.

* [Impact Measurement Worksheet](https://docs.google.com/forms/d/e/1FAIpQLSdwVb7-ES5Ur576oiuo6yeymibZunFDjEcsvyUO2kAkD5xgZQ/viewform)
* [Racial Equity, Inclusion, & Accessibility Worksheet](https://docs.google.com/forms/d/e/1FAIpQLSfp2P6AsLchp5aWDRczbP1Hy4n4VE3HOgVB0AfJoBZCEFTSvg/viewform)
* [Resourcing, Roles and Feasibility Worksheet](https://docs.google.com/forms/d/e/1FAIpQLSdYG3WFjGjU8MxyCuqLpNd-feYNgoopxyehNYx3sz-AmQuVdA/viewform)



<style>
  #formModal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
  }

  #modalContent {
    position: relative;
    width: 80%;
    max-width: 1200px;
    height: 80%;
    margin: 5% auto;
    background-color: #fff;
    padding: 20px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
  }

  #closeFormButton {
    position: absolute;
    top: 10px;
    right: 10px;
    cursor: pointer;
    font-size: 1.5rem;
  }

  #formIframe {
    width: 100%;
    height: 100%;
    border-radius: 10px;
  }
</style>

<script>
  document.getElementById('openFormButton').onclick = function() {
    document.getElementById('formModal').style.display = 'block';
  };
  document.getElementById('closeFormButton').onclick = function() {
    document.getElementById('formModal').style.display = 'none';
  };
</script>