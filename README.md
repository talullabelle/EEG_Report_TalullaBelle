# ERP CORE ERN data

The data are a minimally processed version of the ERP CORE Flanker data set, adapted under a CC BY-SA 4.0 licence (see LICENSE).

Changes made: data were downsampled to 256 Hz, annotations were converted for ease of further processing, and the data were saved in MNE fif format. No other content was altered.

## New event annotations

The original annotations on the left were remapped to the new annotations on the right.

"stimulus/11": "stimulus/compatible/target_left",
"stimulus/12": "stimulus/compatible/target_right",
"stimulus/21": "stimulus/incompatible/target_left",
"stimulus/22": "stimulus/incompatible/target_right",
"response/111": "response/correct/left/compatible",
"response/112": "response/incorrect/left/compatible",
"response/121": "response/correct/left/incompatible",
"response/122": "response/incorrect/left/incompatible",
"response/211": "response/incorrect/right/compatible",
"response/212": "response/correct/right/compatible",
"response/221": "response/incorrect/right/incompatible",
"response/222": "response/correct/right/incompatible"
