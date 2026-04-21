# SE Group 05

# Smart Satellite Image Inpainting & Outpainting System

## Problem Statement  
Satellite images often suffer from missing regions due to cloud cover, sensor errors, or limited capture boundaries. Additionally, satellite imagery is restricted to fixed frames, making it difficult to visualize surrounding areas beyond the captured region.

Traditional methods for restoring or extending such images require manual intervention, domain expertise, and significant time. These approaches are not scalable for real-time or large-scale applications.

This project aims to develop an intelligent system that:
  1. Automatically reconstructs missing regions in satellite images using AI-based inpainting
  2. Expands the visible area beyond the original image using real-world satellite data
  3. Maintains visual consistency, continuity of roads, terrain, and structures

The system combines generative AI with real satellite tile data to provide a practical and efficient solution.



### Tech Stack  

- **Programming Language:** Python
- **AI Model:** Stable Diffusion Inpainting Pipeline
- **Frameworks/Libraries:** PyTorch, Diffusers, NumPy, PIL, Matplotlib
- **Interface:** Jupyter Notebook / Google Colab with ipywidgets
- **Data Source:** ArcGIS World Imagery MapServer (public tile service)
- **Hardware:** GPU (T4 / CUDA supported)

### Expected Outcome  
 
- Generate realistic reconstructions of missing regions in satellite images
- Seamlessly extend images beyond original boundaries using nearby satellite data
- Provide an interactive interface for users to input location (latitude & longitude)
- Enable real-time visualization of inpainting and outpainting results
- Deliver a system that is both AI-driven and grounded in real-world data

## Hypothesis  

If generative AI models like Stable Diffusion are applied to satellite imagery along with real-world spatial data, then it is possible to accurately reconstruct missing regions and extend images while maintaining structural and visual consistency.

--- 

### **Team Members**  

#### **Member 1(Tanisha)**  
- **Role:** AI/Frontend Developer 
- **Responsibilities:**  
  - Model integration and UI interaction 
  - Designing workflow and system logic

#### **Member 2(Shailza)**  
- **Role:** Backend Developer, Data Handling  
- **Responsibilities:**  
  - Satellite data fetching  
  - API and request handling  

#### **Member 3(Srushti)**  
- **Role:** Data & System Design 
- **Responsibilities:**  
  - Managing image processing pipeline
  - Optimizing performance and structure


---

## Project Team Members  

<table>
  <tr align="center">
    <td>
      <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 1 (Team Lead)</b><br>
      Frontend Developer Project Management
    </td>
    <td>
     <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 2</b><br>
      Frontend Developer UI Design
    </td>
    <td>
     <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 3</b><br>
      Backend Developer Data Fetching
    </td>
    <td>
      <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 4</b><br>
      Backend Developer Data Designing
    </td>
  </tr>
</table>
