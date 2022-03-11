# Workshop preparations

## Checklist before the actual workshop

- Location booked including drink/snacks/dinner if applicable?
- Schedule communicated to participant?
- Prerequisites communicated to participant?
- Brownies backed?
- Brownies leaflet printed?
- Prepared a branch specific for this workshop? (eg. [https://github.com/foldingbeauty/kelda/tree/accelerate2_15_03](https://github.com/foldingbeauty/kelda/tree/accelerate2_15_03))
- Prepared a feedback issues in Kelda? (eg. [https://github.com/foldingbeauty/kelda/issues/4](https://github.com/foldingbeauty/kelda/issues/4))

## Checklist before the participant arrives

- Asked the the wifi name/password of the venue and add them to training specific schedule page?
- Connected your laptop and also make sure you logged in to github/gitlab?
- Is the schedule page showed on the screen?

## Training Schedules

{% for page in site.training_specifics %}
- [{{ page.title}}]({{ page.url }})
{% endfor %}
