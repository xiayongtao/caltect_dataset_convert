# caltect_dataset_convert

把caltech行人检测数据集转换为voc格式

1.download.sh下载数据集

2.convert_seq_to_jpg.py将seq文件转换为jpg文件，图像均为640*480.

3.vbb2voc.py将vbb文件转换为xml格式文件。

4.rename_jpg.py将jpg文件命名为和xml文件名一样的。

5.find_xml_with_jpg.py在所有的jpg文件中找出与xml对应的图像。
