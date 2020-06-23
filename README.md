### Data set 

  - MNIST (noise MNIST, origin MNIST) 

### Use Models 

  - Discriminator(DCGAN), Unet
  - MNIST Train


### Image 시각화

  - input Image (noise MNIST)
  - Origin MNIST  
  - Generated Image (UNET)
  - Anomaly Image (diff = noise - Generated)

<img src="img/image-20200623114943733.png" alt="image-20200623114943733" style="zoom:50%;" />


### Discriminated 검증

```python 
dicriminated = disc_model.predict(generated)
```
  -   - 1 : Real, 0 : fake

<img src="img/image-20200623115012836.png" alt="image-20200623115012836" style="zoom:50%;" />