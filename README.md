# GenoMind - AI-Powered Genomic Variant Classifier

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/000-KunalPal/GenoMind/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/000-KunalPal/GenoMind.svg)](https://github.com/000-KunalPal/GenoMind/stargazers)
[![GitHub forks](https.img.shields.io/github/forks/000-KunalPal/GenoMind.svg)](https://github.com/000-KunalPal/GenoMind/network)

**Live Application:** [**https://nexus-call.vercel.app**](https://nexus-call.vercel.app)

GenoMind is a specialized biotech web application that leverages a state-of-the-art Large Language Model (Evo2) to predict the pathogenicity of genetic mutations. It provides a powerful and intuitive tool for computational biology research, enabling rapid and accurate analysis of genetic variants.

![GenoMind Screenshot](https://user-images.githubusercontent.com/83445838/236873413-5381a903-516c-4b1f-963d-42514d9b62f5.png)

## 核心功能

*   **GPU-Accelerated AI Backend**: Engineered and deployed a high-performance Python backend using FastAPI, hosted on Modal's serverless H100 GPU infrastructure. This architecture was designed to serve the computationally intensive Evo2 model for real-time, accurate variant effect prediction.
*   **Modern Full-Stack Interface**: Developed a dynamic and responsive frontend based on the T3 Stack (Next.js, TypeScript), utilizing Tailwind CSS and Shadcn/ui for a polished user experience. The interface allows users to seamlessly search for genes (e.g., BRCA1), browse chromosomes, and visualize genomic data.
*   **Real-World Data Integration & Validation**: Integrated with authoritative external bioinformatics databases, including the NCBI E-utilities and UCSC Genome Browser API, to fetch reference sequences and known variant data. This provides crucial context and allows for real-world validation of model outputs.
*   **Comparative Analysis Engine**: Implemented the core analytical feature: a comparative view that contrasts the AI-driven Evo2 predictions (pathogenic/benign) against the established, gold-standard ClinVar classifications, complete with prediction confidence scores. This allows for direct assessment of the model's performance against human-curated data.

## 技术栈

*   **Frontend**: Next.js, TypeScript, Tailwind CSS, Shadcn/ui
*   **Backend**: Python, FastAPI
*   **AI Model**: Evo2 (Large Language Model)
*   **Infrastructure**: Modal (Serverless H100 GPU), Vercel

## 开始

To get a local copy up and running, follow these simple steps.

### 前提条件

*   Node.js (v18.17.0 or later)
*   npm
*   Python (3.9 or later)

### 安装

1.  **Clone the repo**
    ```sh
    git clone https://github.com/000-KunalPal/GenoMind.git
    ```
2.  **Install NPM packages**
    ```sh
    npm install
    ```
3.  **Install Python packages**
    ```sh
    pip install -r requirements.txt
    ```

### 运行应用程序

1.  **Start the frontend development server**
    ```sh
    npm run dev
    ```
2.  **Start the backend server**
    ```sh
    # Instructions for running the FastAPI backend
    ```

## 用法

1.  Navigate to the live application at [https://nexus-call.vercel.app](https://nexus-call.vercel.app).
2.  Enter a gene of interest (e.g., *BRCA1*) in the search bar.
3.  Browse the chromosome and select a specific genetic variant.
4.  View the AI-powered pathogenicity prediction from the Evo2 model.
5.  Compare the model's prediction with the established ClinVar classification.

## 贡献

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 许可证

Distributed under the MIT License. See `LICENSE` for more information.

## 联系方式

Kunal Pal - [@\_KunalPal](https://twitter.com/_KunalPal) - kunalpal.work@gmail.com

Project Link: [https://github.com/000-KunalPal/GenoMind](https://github.com/000-KunalPal/GenoMind)
