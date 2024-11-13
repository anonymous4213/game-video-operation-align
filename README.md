# Alignment between Game Video and User Operations with Vision Language Models

## Overview
Game AI's evolution plays a critical role in shaping the technological landscape and enriching user experiences. A key challenge in this domain is detecting and interpreting user operations from video data, which can be leveraged to better understand player strategies, improve AI adaptability, and enhance the complexity of in-game AI responses. In this work, we implements the **Large-Models-Only (LMO)** framework, which utilizes Vision Language Models (VLMs), such as LLaVA, MiniCPM-V, and QWen2-VL, to detect these operations. By proposing the LMO framework, we aim to provide a more robust and scalable solution to capturing user operations across different games, ultimately advancing the field of Game AI and paving the way for more dynamic, challenging, and adaptive gaming environments.

This repository provides the code and resources necessary to evaluate these VLMs for recognizing user actions within game video segments, enabling a more sophisticated, non-intrusive approach to data collection. The LMO framework is designed to overcome the limitations of traditional data collection methods, which often involve direct tracking of user inputs and may influence player behavior.

## Approach
We employ several state-of-the-art open-source Vision Language Models—LLaVA, MiniCPM-V, and QWen2-VL—to analyze player actions in game footage. These models bring together capabilities in computer vision and natural language processing, capturing the visual and contextual nuances of gameplay without the need for manual or intrusive data collection methods. Our LMO framework not only increases scalability by reducing dependence on control customizations across games but also introduces a high degree of generalizability for Game AI research.

## Key Features
Non-Intrusive Player Action Recognition: Detects user operations in game videos without disrupting gameplay.
High-Performance VLMs: Utilizes powerful Vision Language Models for accurate alignment with player actions.
Enhanced Game AI Training Data: Generates sophisticated datasets from detected player operations to train more responsive and adaptive Game AI.
