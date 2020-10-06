# Instagram Influencer Dataset


## Dataset download link
https://sites.google.com/site/sbkimcv/dataset

- Post metadata (JSON files): ~37 GB

- Image (JPEG files): ~189 GB


## Dataset description
As a part of the '[Influencer Marketing Research](https://sites.google.com/site/sbkimcv/research?authuser=0#h.p_ID_38)', I collected data from Instagram and share it for the research purpose. 
The dataset contains 33,935 influencers with their 10,180,500 Instagram posts (300 posts per influencer).
The dataset includes two types of files, post metadata and image files.
Post metadata files are in JSON format and it contains following information: caption, usertags, hashtags, timestamp, sponsorship, likes, comments, etc.
Image files are in JPEG format and the dataset contains 12,933,406 image files since a post can have more than one image file.
If a post has only one image file then JSON file and the corresponding image files have the same name.
However, if a post has more than one image then JSON file and corresponding image files have different names.
Therefore, we also provide a JSON-Image_mapping file that shows a list of image files coreesponds to a post metadata.

Influencers are classified into the following nine categories:
1. Beauty
2. Family
3. Fashion
4. Fitness
5. Food
6. Interior
7. Pet
8. Travel
9. Other
![DatasetImage](https://github.com/ksb2043/instagram_influencer_dataset/blob/master/image2.png)

The detailed of data collection method and the categories of influencers and posts are described in the paper "[Multimodal Post Attentive Profiling for Influencer Marketing](https://dl.acm.org/doi/abs/10.1145/3366423.3380052)" published in The Web Conference '20.
![Framework](https://github.com/ksb2043/instagram_influencer_dataset/blob/master/image1.png)

## Citation for the Instagram Influencer Dataset

"Multimodal Post Attentive Profiling for Influencer Marketing," Seungbae Kim, Jyun-Yu Jiang, Masaki Nakada, Jinyoung Han and Wei Wang.  In Proceedings of the 2020 World Wide Web Conference (WWW '20), ACM, 2020.

```
@inproceedings{kim2020multimodal,
  title={Multimodal Post Attentive Profiling for Influencer Marketing},
  author={Kim, Seungbae and Jiang, Jyun-Yu and Nakada, Masaki and Han, Jinyoung and Wang, Wei},
  booktitle={Proceedings of The Web Conference 2020},
  pages={2878--2884},
  year={2020}
}
```
