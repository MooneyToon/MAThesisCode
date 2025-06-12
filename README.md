# MAThesisCode
Full code used in the analysis for MA Thesis: Comparing infant-aligned artificial neural networks’ (ANNs) categorization of objects to actual infant EEG

### Pretrained Weights

This project uses model weights from two sources:

**TC-SAY-resnext50**  
Provided by [eminorhan/baby-vision](https://github.com/eminorhan/baby-vision), trained on the SAYCam dataset.  
We do **not redistribute** these weights directly; instead, we download them from their official GitHub-hosted release:  
🔗 [Download TC-SAY_resnext50_16_0.5.pth.tar](https://github.com/eminorhan/baby-vision/releases/download/v1.0/TC-SAY_resnext50_16_0.5.pth.tar)  
Please see their [MIT License](https://github.com/eminorhan/baby-vision/blob/main/LICENSE) and cite their work if you use these weights.

---

**VOneResNet50 and VOneCORnet-S**  
Provided by the [DiCarlo lab’s VOneNet repository](https://github.com/dicarlolab/vonenet).  
You can manually download the pretrained weights here:  

- [VOneResNet50 pretrained weights](https://www.crcv.ucf.edu/data/VOneNet/vone_resnet50-5c69b485.pth)  
- [VOneCORnet-S pretrained weights](https://www.crcv.ucf.edu/data/VOneNet/vone_cornet_s-ec1b3f9e.pth)  

We do **not redistribute** these files ourselves.  
Please see their [LICENSE](https://github.com/dicarlolab/vonenet/blob/master/LICENSE) and cite their original work.
