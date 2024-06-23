## RGBL-Tracking-Results-Datasets-and-Methods

**An investigation for RGBL tracking. 
Hopefully, it can help other researchers become familiar with multi-modal tracking as soon as possible.
This repository is started on 27/12/2023, and will keep on updating.**

-----
>This repository will give a detail investigation of the RGBL tracking community, including the Datasets, Results, and the Methods.
> 
>  - [x] Datasets
>  - [x] Results
>  - [x] Methods
>  -  ...
-----

## Survey Papers


## Datasets

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| UniMod1K| IJCV'2024 |[UniMod1K](https://github.com/xuefeng-zhu5/UniMod1K) |RGB+D+L: UniMod1K: Towards a More Universal Large-Scale Dataset and Benchmark for Multi-modal Learning|
| WebUAV-3M| TPAMI'2023 | [WebUAV-3M](https://github.com/983632847/WebUAV-3M) | RGB+L+Audio: WebUAV-3M: A Benchmark for Unveiling the Power of Million-Scale Deep UAV Tracking|

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| WebUOT-1M| Arxiv'2024 |[WebUOT-1M](https://github.com/983632847/Awesome-Multimodal-Object-Tracking) |WebUOT-1M: Advancing Deep Underwater Object Tracking with A Million-Scale Benchmark|
| VastTrack| Arxiv'2024 |[VastTrack](https://github.com/HengLan/VastTrack) |VastTrack: Vast Category Visual Object Tracking|
| MGIT| NIPS'2023 |[MGIT](http://videocube.aitestunion.com/) |A Multi-modal Global Instance Tracking Benchmark (MGIT): Better Locating Target in Complex Spatio-temporal and Causal Relationship|
| TNL2K| CVPR'2021 | [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit)|Towards More Flexible and Accurate Object Tracking with Natural Language: Algorithms and Benchmark|
| LaSOT_EXT| IJCV'2021 |[LaSOT_EXT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Large-scale Single Object Tracking Benchmark|
| LaSOT| CVPR'2019 | [LaSOT](https://github.com/HengLan/LaSOT_Evaluation_Toolkit)|LaSOT: A High-quality Benchmark for Large-scale Single Object Tracking|
| OTB99-L| CVPR'2017 | [OTB99-L](https://github.com/QUVA-Lab/lang-tracker) |Tracking by Natural Language Specification|

-----
## Results


<table>
    <tr> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="3">OTB99_L</th> 
        <th colspan="3">TNL2K</th> 
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> PR</td>
      	<td> NPR</td>
    	<td> SR</td>
    	<td> PR</td>
      	<td> NPR</td>
   	<td> SR</td>
    </tr>
    <tr>
    	<td> QueryNLT</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> 88.2</td>
      	<td> 82.4</td>
    	<td> 66.7</td>
    	<td> 58.7</td>
      	<td> 75.6</td>
   	<td> 57.8</td>
    </tr>
    <tr>
    	<td> DTLLM-VLT</td>
    	<td>CVPRW'2024</td>
	<td></td>
    	<td> 92.5</td>
      	<td> 86.0</td>
    	<td> 71.3</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> MFAVLT</td>
    	<td>Remote Sensing'2024</td>
	<td></td>
    	<td> 87.2</td>
      	<td> </td>
    	<td> 65.4</td>
    	<td> 51.3</td>
      	<td> </td>
   	<td> 44.7</td>
    </tr>
    <tr>
    	<td> OSDT</td>
    	<td>TCSVT'2024</td>
	<td>67</td>
    	<td> 86.7</td>
      	<td> 78.0</td>
    	<td> 66.2</td>
    	<td> 61.5</td>
      	<td> 76.2</td>
   	<td> 59.3</td>
    </tr>
    <tr>
    	<td> TTCTrack</td>
    	<td>TCSVT'2024</td>
	<td>52</td>
    	<td> </td>
      	<td> </td>
    	<td> 70.1</td>
    	<td> </td>
      	<td> </td>
   	<td> 58.1</td>
    </tr>
    <tr>
    	<td> MMTrack</td>
    	<td>TCSVT'2024</td>
	<td></td>
    	<td> 91.8</td>
      	<td> </td>
    	<td> 70.5</td>
    	<td> 59.4</td>
      	<td> 75.2</td>
   	<td> 58.6</td>
    </tr>
    <tr>
    	<td> UVLTrack</td>
    	<td>AAAI'2024</td>
	<td></td>
    	<td> 92.0</td>
      	<td> </td>
    	<td> 71.1</td>
    	<td> 69.3</td>
      	<td> </td>
   	<td> 64.9</td>
    </tr>
    <tr>
    	<td> All in One</td>
    	<td>ICCV'2023</td>
	<td>60</td>
    	<td> 93.0</td>
      	<td> </td>
    	<td> 71.0</td>
    	<td> 57.2</td>
      	<td> </td>
   	<td> 55.3</td>
    </tr>
    <tr>
    	<td>SATracker</td>
    	<td>Arxiv'2023</td>
	<td></td>
    	<td> 94.3</td>
      	<td> </td>
    	<td> 74.2</td>
    	<td> 64.4</td>
      	<td> 78.4</td>
   	<td> 61.6</td>
    </tr>
    <tr>
    	<td>CiteTracker</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 92.2</td>
      	<td> 85.1</td>
    	<td> 69.6</td>
    	<td> 59.6</td>
      	<td> </td>
   	<td> 57.7</td>
    </tr>
    <tr>
    	<td>VLT_OST</td>
    	<td>Arxiv'2023</td>
	<td></td>
    	<td> 95.0</td>
      	<td> </td>
    	<td> 77.7</td>
    	<td> 54.5</td>
      	<td> </td>
   	<td> 55.7</td>
    </tr>
    <tr>
    	<td>JointNLT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> 85.6</td>
      	<td> </td>
    	<td> 65.3</td>
    	<td> 58.1</td>
      	<td> </td>
   	<td> 56.9</td>
    </tr>
    <tr>
    	<td>VLATrack</td>
    	<td>RICAI'2023</td>
	<td></td>
    	<td> 93.3</td>
      	<td> </td>
    	<td> 72.0</td>
    	<td> 65.9</td>
      	<td> 79.7</td>
   	<td> 62.6</td>
    </tr>
   <tr>
    	<td>OVLM</td>
    	<td>TMM'2023</td>
	<td></td>
    	<td> </td>
      	<td> </td>
    	<td> </td>
    	<td> 69.3</td>
      	<td> 82.6</td>
   	<td> 64.7</td>
    </tr>
   <tr>
    	<td>TransNLT</td>
    	<td>TCSVT'2023</td>
	<td></td>
    	<td> 87.0</td>
      	<td> </td>
    	<td> 67.0</td>
    	<td> 57.0</td>
      	<td> 75.0</td>
   	<td> 57.0</td>
    </tr>
   <tr>
    	<td>DecoupleNLT</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 94.8</td>
      	<td> </td>
    	<td> 73.8</td>
    	<td> 56.0</td>
      	<td> </td>
   	<td> 56.7</td>
    </tr>
   <tr>
    	<td>PTG</td>
    	<td>PRL'2023</td>
	<td></td>
    	<td> 91.5</td>
      	<td> </td>
    	<td> 70.6</td>
    	<td> </td>
      	<td> 61.7</td>
   	<td> 56.0</td>
    </tr>
   <tr>
    	<td>AdaRS</td>
    	<td>CVPRW'2023</td>
	<td> </td>
    	<td> 91.0</td>
      	<td> </td>
    	<td> 69.0</td>
    	<td> 45.0</td>
      	<td> 52.0</td>
   	<td> 44.0</td>
    </tr>
    <tr>
    	<td>VLT_TT</td>
    	<td>NIPS'2022</td>
	<td></td>
    	<td> 93.9</td>
      	<td> </td>
    	<td> 77.2</td>
    	<td> 54.2</td>
      	<td> </td>
   	<td> 55.0</td>
    </tr>
    <tr>
    	<td>CapsuleNLT</td>
    	<td>ACMMM'2021</td>
	<td></td>
    	<td> 92.4</td>
      	<td> </td>
    	<td> 71.1</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>SNLT</td>
    	<td>CVPR'2021</td>
	<td> </td>
    	<td> 84.8</td>
      	<td> 80.4</td>
    	<td> 66.6</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>RTTNLD</td>
    	<td>WACV'2020</td>
	<td> </td>
    	<td> 79.0</td>
      	<td> 73.0</td>
    	<td> 61.0</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
</table>


<table>
    <tr> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="3">LaSOT</th> 
        <th colspan="3">LaSOT_EXT</th> 
    </tr>
    <tr>
    	<td> QueryNLT</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> 63.5</td>
      	<td> 69.6</td>
    	<td> 59.9</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> DTLLM-VLT</td>
    	<td>CVPRW'2024</td>
	<td></td>
    	<td> 75.7</td>
      	<td> 82.2</td>
    	<td> 69.9</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> MFAVLT</td>
    	<td>Remote Sensing'2024</td>
	<td></td>
    	<td> 55.6</td>
      	<td> </td>
    	<td> 55.3</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> OSDT</td>
    	<td>TCSVT'2024</td>
	<td>67</td>
    	<td> 68.6</td>
      	<td> 73.4</td>
    	<td> 64.3</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> TTCTrack</td>
    	<td>TCSVT'2024</td>
	<td>52</td>
    	<td> </td>
      	<td> </td>
    	<td> 67.6</td>
    	<td> </td>
      	<td> </td>
   	<td> 48.8</td>
    </tr>
    <tr>
    	<td> MMTrack</td>
    	<td>TCSVT'2024</td>
	<td></td>
    	<td> 75.7</td>
      	<td> 82.3</td>
    	<td> 70.0</td>
    	<td> 55.3</td>
      	<td> 59.9</td>
   	<td> 49.4</td>
    </tr>
    <tr>
    	<td> UVLTrack</td>
    	<td>AAAI'2024</td>
	<td></td>
    	<td> 78.7</td>
      	<td> </td>
    	<td> 71.4</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> All in One</td>
    	<td>ICCV'2023</td>
	<td>60</td>
    	<td> 78.5</td>
      	<td> 82.4</td>
    	<td> 71.7</td>
    	<td> 66.0</td>
      	<td> </td>
   	<td> 54.5</td>
    </tr>
    <tr>
    	<td>SATracker</td>
    	<td>Arxiv'2023</td>
	<td></td>
    	<td> 79.6</td>
      	<td> </td>
    	<td> 72.4</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>CiteTracker</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 75.7</td>
      	<td> 78.6</td>
    	<td> 69.7</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>VLT_OST</td>
    	<td>Arxiv'2023</td>
	<td></td>
    	<td> 77.0</td>
      	<td> </td>
    	<td> 70.5</td>
    	<td> 54.8</td>
      	<td> </td>
   	<td> 48.6</td>
    </tr>
    <tr>
    	<td>JointNLT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> 63.6</td>
      	<td> </td>
    	<td> 60.4</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>VLATrack</td>
    	<td>RICAI'2023</td>
	<td></td>
    	<td> 73.8</td>
      	<td> 77.7</td>
    	<td> 68.2</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
   <tr>
    	<td>OVLM</td>
    	<td>TMM'2023</td>
	<td></td>
    	<td> </td>
      	<td> </td>
    	<td> </td>
    	<td> 74.2</td>
      	<td> 77.6</td>
   	<td> 67.7</td>
    </tr>
   <tr>
    	<td>DecoupleNLT</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 75.3</td>
      	<td> </td>
    	<td> 71.2</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
   <tr>
    	<td>PTG</td>
    	<td>PRL'2023</td>
	<td> </td>
    	<td> 70.8</td>
      	<td> </td>
    	<td> 66.4</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
   <tr>
    	<td>AdaRS</td>
    	<td>CVPRW'2023</td>
	<td> </td>
    	<td> 56.0</td>
      	<td> </td>
    	<td> 53.0</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>VLT_TT</td>
    	<td>NIPS'2022</td>
	<td></td>
    	<td> 75.4</td>
      	<td> </td>
    	<td> 68.8</td>
    	<td> 57.4</td>
      	<td> </td>
   	<td> 49.7</td>
    </tr>
    <tr>
    	<td>CapsuleNLT</td>
    	<td>ACMMM'2021</td>
	<td></td>
    	<td> 63.3</td>
      	<td> 71.1</td>
    	<td> 61.5</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>SNLT</td>
    	<td>CVPR'2021</td>
	<td> </td>
    	<td> 57.4</td>
      	<td> 63.6</td>
    	<td> 54.0</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td>RTTNLD</td>
    	<td>WACV'2020</td>
	<td> </td>
    	<td> 35.0</td>
      	<td> 43.0</td>
    	<td> 35.0</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
  <tr>
    	<td>TransNLT</td>
    	<td>TCSVT'2023</td>
	<td></td>
    	<td> 63.0</td>
      	<td> </td>
    	<td> 60.0</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
</table>


<table>
    <tr> 
        <th colspan="1"></th> 
	<th colspan="1"></th> 
	<th colspan="1"></th> 
        <th colspan="3">MGIT</th> 
        <th colspan="3">VastTrack</th> 
            <th colspan="3">WebUOT-1M</th> 
	            <th colspan="3">WevUAV-3M</th> 
	            <th colspan="3">WevUAV-3M</th> 
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> PR</td>
      	<td> NPR</td>
    	<td> SR</td>
    	<td> PR</td>
      	<td> NPR</td>
   	<td> SR</td>
      	<td> PR</td>
      	<td> NPR</td>
   	<td> SR</td>s
      	<td> PR</td>
      	<td> NPR</td>
   	<td> SR</td>
    </tr>
    <tr>
    	<td> DTLLM-VLT</td>
    	<td>CVPRW'2024</td>
	<td></td>
    	<td> 54.6</td>
      	<td> 78.5</td>
    	<td> 74.4</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> UVLTrack</td>
    	<td>AAAI'2024</td>
	<td></td>
    	<td> </td>
      	<td> </td>
    	<td> </td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> 52.5</td>
      	<td> 60.0</td>
   	<td> 55.8</td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> All in One</td>
    	<td>ICCV'2023</td>
	<td>60</td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
	<td> 53.1</td>
      	<td> 61.5</td>
   	<td> 57.1</td>
	<td> 71.5</td>
      	<td> 60.5</td>
   	<td> 56.8</td>
    </tr>
    <tr>
    	<td> JointNLT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
	<td> 25.5</td>
      	<td> 34.9</td>
   	<td> 32.7</td>
	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> CiteTracker</td>
    	<td>ICCV'2023</td>
	<td> </td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
	<td> 49.3</td>
      	<td> 58.4</td>
   	<td> 54.6</td>
	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>
    <tr>
    	<td> VLT_TT</td>
    	<td>NIPS'2022</td>
	<td> </td>
    	<td> </td>
      	<td> </td>
   	<td> </td>
      	<td> </td>
      	<td> </td>
   	<td> </td>
	<td> 41.7</td>
      	<td> 52.1</td>
   	<td> 48.3</td>
	<td> </td>
      	<td> </td>
   	<td> </td>
    </tr>

</table>

-----
## Contributors
- [Zhangyong Tang](https://github.com/Zhangyong_Tang)
- [PRCI-Lab](https://github.com/PRCI-Lab)

**Questions**

If you have any questions, please contact zhangyong_tang_jnu@163.com, and wechat: Tzy18861871359 is also welcomed.



 
