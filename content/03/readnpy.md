# How I read and saved the files: 

```Python
np.save('dwi_image.npy', dwi_image)

dwi_image2 = np.load('dwi_image.npy')
```

***

```Python
np.save('Dp.npy', Dp)
np.save('Dp_truth.npy', Dp_truth)
np.save('Dt.npy', Dt)
np.save('Dt_truth.npy', Dt_truth)
np.save('Fp.npy', Fp)
np.save('Fp_truth.npy', Fp_truth)


Dp2 = np.load('Dp.npy')
Dp_truth2 = np.load('Dp_truth.npy')
Dt2 = np.load('Dt.npy')
Dt_truth2 = np.load('Dt_truth.npy')
Fp2 = np.load('Fp.npy')
Fp_truth2 = np.load('Fp_truth.npy')
```

