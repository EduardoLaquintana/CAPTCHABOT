# CAPTCHABOT
Design a BOT capable of beating reCAPTCHA challenges

Setup
Plan/organize
Read reCapthca v3 docs
Github repo (+ test) / live shared coding env?
Python / TensorFlow / AWS account + access

Model
Find captcha specific dataset (images first, no text/numbers) Done (drive folder)
Use data augmentation online (while training, less storage needed, see google dev code) to have more data (TF ImageDataGenerator module, see Kaggle)
Pre-trained models (inception v4?) + tuned top (hyperopt?)

Possible milestones
1) image recognition (multi-class classification)
2) voting on 9 images, define a confidence threshold (multi-class classification + voting)
3) Connect to API or scrape a website to test live safely + button click (production) and obtain human-like (~1.0) scores

Other
GPU vs CPU
Separate tasks, or do same but diff paths
Future: try one-shot learning, structured learning
