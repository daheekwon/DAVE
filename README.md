# DAVE

Dahee Kwon · Haeun Lee · Jaesik Choi

This is the official implementation of **Breaking the Lock-in: Diversifying Text-to-Image Generation via Representation Modulation**, published in ICML 2026.

## Abstract
Recent text-to-image models produce high-quality, prompt-aligned images, but samples generated from the same prompt often look overly similar. We investigate this homogeneity by analyzing intermediate Transformer features and find that their spatial average, or DC component, quickly becomes similar across different seeds early in generation. This early convergence locks generation trajectories into similar outcomes and reduces later variation. Motivated by this, we propose DC Attenuation for diVersity Enhancement (**DAVE**), a training-free representation-level intervention that attenuates the early DC component. DAVE improves prompt-consistent diversity with negligible overhead while maintaining image quality.

![image](./dave-main.png)

## Code 
The code will be released upon publication.

## Contact 
For questions, research discussions, or collaboration opportunities, please feel free to contact [Dahee Kwon](mailto:dahee.kwon@kaist.ac.kr)
