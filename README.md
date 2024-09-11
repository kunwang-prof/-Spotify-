# 基于Spotify的个性化音乐推荐系统

•	数据准备：Spotify抓取个人播放列表歌曲构建音乐数据集。深入研究Spotify官方文档，精选出14项核心特征，分类为'信息特征'和'音频特征'。
<img width="742" alt="Screenshot 2024-09-11 at 14 24 57" src="https://github.com/user-attachments/assets/92bd1f0f-471d-4307-8021-8e27ef8a42ea">



•	数据分析：对数据集中的各项指标进行可视化分析，把握个人音乐喜好；使用PCA对14个特征实施降维，并运用Kmeans算法实现音乐聚类。
<img width="424" alt="Screenshot 2024-09-11 at 14 24 07" src="https://github.com/user-attachments/assets/b70c0f7a-6d11-4960-980a-920a2627a345">



•	推荐系统：结合个人音乐喜好，采用Euclidean Distance与Cosine Similarity进行歌曲相似性评估，从而实现了一款基于内容的个性化音乐推荐系统。

