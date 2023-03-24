---
title: Courses
date: '2021-09-29'
type: book
weight: 40
---

## Overview

<div style="text-align: justify;">
  On this page, you would find information about courses that I am currently teaching as well courses that I had taught in the past.
  
</div>
<br>

[**Computer Network and Internet Technology | Bachelor**](./rnit)

**Overview:** This course consists of two parts, lecture and practical, also called Proseminar (PS). The PS aims to deepen the theoretical understanding and involves exercises and simple programming exercises. The course is offered during the winter semester and is worth 3 ECTS.

<style>
  .btn-feedback {
    display: inline-block;
  }
  .btn-feedback-negative {
    margin-left: 1em;
  }
  .feedback--response {
    display: none;
    margin-top: 1em;
  }
  .feedback--response__visible {
    display: block;
  }
</style>
<div class="d-print-none widget--feedback">
  <h2 class="feedback--title">Feedback</h2>
  <p class="feedback--question">Was this page helpful?</p>
  <p class="feedback--response feedback--response-positive">
    🙏
  </p>
  <p class="feedback--response feedback--response-negative">
    🙏
  </p>
  <button class="btn btn-primary mb-4 btn-feedback btn-feedback-positive">
    😍 Yes
  </button>
  <button class="btn btn-primary mb-4 btn-feedback btn-feedback-negative">
    😡 No
  </button>
</div>
<script>
  const btnYes = document.querySelector('.btn-feedback-positive');
  const btnNo = document.querySelector('.btn-feedback-negative');
  const responseYes = document.querySelector('.feedback--response-positive');
  const responseNo = document.querySelector('.feedback--response-negative');
  const disableButtons = () => {
    btnYes.disabled = true;
    btnNo.disabled = true;
  };
  const sendFeedback = (value) => {
    if (typeof gtag !== 'function') return;
    gtag('event', 'click', {
      'event_category': 'page_rating',
      'event_label': window.location.pathname,
      'value': value,
      'transport_type': 'beacon',
      'event_callback': function () {
        console.debug(`✅ Feedback sent ${value}`);
      }
    });
  };
  btnYes.addEventListener('click', () => {
    console.debug('Feedback response: 😍');
    responseYes.classList.add('feedback--response__visible');
    disableButtons();
    sendFeedback(1);
  });
  btnNo.addEventListener('click', () => {
    console.debug('Feedback response: 😡');
    responseNo.classList.add('feedback--response__visible');
    disableButtons();
    sendFeedback(0);
  });
</script>
