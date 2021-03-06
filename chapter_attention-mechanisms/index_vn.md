<!--
# Attention Mechanisms
-->

# Cơ chế Tập trung
:label:`chap_attention`

<!--
As a bit of a historical digression, attention research is an enormous field with a long history in cognitive neuroscience.
Focalization, concentration of consciousness are of the essence of attention, which enable the human to prioritize the perception in order to deal effectively with others.
As a result, we do not process all the information that is available in the sensory input.
At any time, we are aware of only a small fraction of the information in the environment.
In cognitive neuroscience, there are several types of attention such as selective attention, covert attention, and spatial attention.
The theory ignites the spark in recent deep learning is the *feature integration theory* of the selective attention, 
which was developed by Anne Treisman and Garry Gelade through the paper :cite:`Treisman.Gelade.1980` in 1980.
This paper declares that when perceiving a stimulus, features are registered early, automatically, and in parallel, while objects are identified separately and at a later stage in processing.
The theory has been one of the most influential psychological models of human visual attention.
-->

Tản mạn một chút về lịch sử, sự tập trung là một lĩnh vực nghiên cứu rộng lớn và lâu đời trong ngành thần kinh học nhận thức.
Trọng tâm của lĩnh vực là sự tập trung nhận thức vào một vài đặc điểm nào đó, điều này cho phép chúng ta ưu tiên tri giác của mình để giải quyết các công việc một cách hiệu quả.
Kết quả là chúng ta không xử lý toàn bộ những thông tin thu được từ các giác quan.
Tại một thời điểm, chúng ta chỉ tiếp nhận một lượng nhỏ thông tin từ môi trường.
Trong ngành thần kinh học nhận thức, tồn tại một vài dạng tập trung ví dụ cơ chế tập trung có chọn lọc, tập trung ngầm, và tập trung về không gian.
Thuyết tập trung khơi gợi nguồn cảm hứng trong lĩnh vực học sâu gần đây đó là *thuyết tích hợp đặc trưng* trong cơ chế tập trung có chọn lọc được phát triển bởi Anne Treisman và Garry Gelade trong :cite:`Treisman.Gelade.1980` vào năm 1980.
Bài báo này phát biểu rằng khi có kích thích thị giác, đầu tiên ta tiếp nhận các đặc trưng một cách tự động và đồng thời, trong khi các sự vật sẽ được xác định riêng biệt ở pha tiếp theo trong quá trình xử lý. <!--feature dịch là đặc trưng nghe k xuôi bằng tín hiệu trong neuroscience: ý kiến cá nhân-->
Lý thuyết này trở thành một trong những mô hình tâm lý học về cơ chế tập trung thị giác của con người có nhiều ảnh hưởng nhất.


<!--
However, we will not indulge in too much theory of attention in neuroscience, but rather focus on applying the attention idea in deep learning,
where attention can be seen as a generalized pooling method with bias alignment over inputs.
In this chapter, we will provide you with some intuition about how to transform the attention idea to the concrete mathematics models, and make them work.
-->

Tuy nhiên, chúng ta sẽ không đi sâu vào thuyết tập trung trong ngành thần kinh học mà sẽ tìm hiểu cách áp dụng ý tưởng của cơ chế chú ý, tập trung vào học sâu.
Ở đây, cơ chế tập trung có thể coi là khái quát hoá của phép gộp, với từng trọng số trên mỗi giá trị đầu vào.
Trong chương này, chúng tôi giúp bạn hình dung cách biến ý tưởng về cơ chế tập trung thành các mô hình toán học cụ thể có thể hoạt động được.

```toc
:maxdepth: 2

attention_vn
seq2seq-attention_vn
transformer_vn
```


## Những người thực hiện
Bản dịch trong trang này được thực hiện bởi:

* Đoàn Võ Duy Thanh
* Nguyễn Văn Quang
