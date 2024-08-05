[Opencv GPU Windows10]
Download link: https://canhoxinh.net/git/opencv410_GPU_M6000_124_897.zip
1.Install driver for GPU (M6000)
2.Download and install cudatoolkit (cuda12.4 and cuDNN8.9.7)
3.Install anaconda (python3.9.13)
4.Extract opencv410_GPU_M6000_124_897.zip to folder "opencv410_GPU_M6000_124_897"
5.cmake --build "~/opencv410_GPU_M6000_124_897" --target INSTALL --config Release
