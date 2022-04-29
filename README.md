基本配置：

python3.8+"conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch"(https://pytorch.org/)

![image-20220429174029026](https://user-images.githubusercontent.com/58418735/165923119-57eb90dd-e281-42a9-8ea3-76500fcb24dd.png)


```python
pip install -r requirements.txt
```

已经把所需东西均配置好，直接运行train.py即可。


## **最终效果**

### 图片
![000295](https://user-images.githubusercontent.com/58418735/165923664-5f534eca-137e-43d5-8f8f-a98677c2cf66.jpg)

### 视频

![image-20220429175838756](https://user-images.githubusercontent.com/58418735/165923851-fa41fe14-f521-4863-8f59-e4b9129d964a.png)



视频/图片/摄像头 的选择方式再‘detect.py’的parser.add_argument('--source')的default=里修改
