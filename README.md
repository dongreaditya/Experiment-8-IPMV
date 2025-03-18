# Experiment-8-IPMV
A **Butterworth High-Pass Filter (BHPF)** in **Image Processing and Machine Vision (IPMV)** enhances high-frequency details by removing low-frequency components like gradual intensity variations (blurring). Unlike an **ideal high-pass filter**, it provides a **smooth transition** instead of a sharp cutoff, minimizing artifacts.  

The filter is defined by:  
\[
H(u,v) = \frac{1}{1 + \left(\frac{D_0}{D(u,v)}\right)^{2n}}
\]
where **\(D(u,v)\)** is the distance from the center, **\(D_0\)** is the cutoff frequency, and **\(n\)** controls the sharpness of the transition.  

### **Effects:**  
- **Low \(n\)** → Gradual enhancement of edges and fine details.  
- **High \(n\)** → Sharper edge detection but may introduce noise.  

BHPF is widely used in **edge detection, feature extraction, and image sharpening**, making it useful in applications requiring enhancement of fine details. 🚀
