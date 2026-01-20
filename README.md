🎙️ VoiceBridge : 

Severity-Aware Dysarthric Speech Analysis using Conformer Networks & GANs

<p align="center"> <b>Bridging impaired speech and intelligibility through deep learning</b> </p> <p align="center"> <img src="https://img.shields.io/badge/Domain-Speech%20AI-blue"/> <img src="https://img.shields.io/badge/Focus-Dysarthria-orange"/> <img src="https://img.shields.io/badge/Model-Conformer-green"/> <img src="https://img.shields.io/badge/Augmentation-GANs-purple"/> <img src="https://img.shields.io/badge/Status-Research%20Ready-success"/> </p>

🔗 What is VoiceBridge?

VoiceBridge is a research-oriented deep learning framework designed to improve the analysis of dysarthric speech by:

Accurately classifying dysarthria severity (mild / moderate / severe)

Improving speech intelligibility

Bridging the performance gap caused by data scarcity and class imbalance, especially for severe dysarthria

The system combines Conformer-based speech modeling with a carefully selected GAN-based data augmentation strategy, evaluated in a two-phase framework.


## 🔄 Two-Phase Pipeline

**VoiceBridge** follows a **two-phase pipeline** designed for fair evaluation and robust performance improvement:

### 🟦 Phase 1: Learning & Comparison
> 🧠 **Goal:** Build a strong baseline and objectively compare GAN models  
- Train a Conformer-based severity classifier  
- Evaluate multiple GAN architectures independently  
- Select the best-performing GAN using objective metrics  

### 🟩 Phase 2: Augmentation & Improvement
> 🚀 **Goal:** Use the best GAN to improve real-world performance  
- Apply severity-aware data augmentation  
- Retrain the Conformer model  
- Measure classification and intelligibility improvements  



<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/a49d44d3-2a66-47bb-8532-83d5b4e26880" />
🚨 Why This Project Matters

Dysarthric speech analysis faces three major challenges:

❌ Limited labeled datasets

❌ Severe class imbalance (very few severe samples)

❌ Poor generalization for highly distorted speech

VoiceBridge directly addresses all three, making it relevant for:

Assistive speech technologies

Clinical speech assessment

Healthcare AI research

Robust ASR for impaired speech

