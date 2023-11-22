## Mask2Former 

Enter in cmd-line:
For video instance segmentation:
1. cd in .../Mask2Former/demo_video
2. 'python demo.py --config-file ../configs/youtubevis_2021/video_maskformer2_R50_bs16_8ep.yaml --video-input ~/Project/video/short2_300.mp4 --opts MODEL.WEIGHTS ../../models/mask2former/model_final_b8aae2.pkl' where config-file contains model-config and MODEL.WEIGHT the model weights 
3. Youtube 21 swin_T model:
python demo.py --config-file ~/Project/Mask2Former/configs/youtubevis_2021/swin/video_maskformer2_swin_tiny_bs16_8ep.yaml --video-input ~/Project/video/short2_300.mp4 --opts MODEL.WEIGHTS ~/Project/models/mask2former/YT21_swin_T.pkl
4. Youtube 19 swin_T model:
python demo.py --config-file ~/Project/Mask2Former/configs/youtubevis_2019/swin/video_maskformer2_swin_tiny_bs16_8ep.yaml --video-input ~/Project/video/short2_300.mp4 --opts MODEL.WEIGHTS ~/Project/models/mask2former/YT19_swin_T.pkl