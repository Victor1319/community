## Community Meeting Minutes

### 2020/10/13
Topic:
- ChubaoFS Java SDK and Hadoop Plugin Design and shell demo.

Speaker:
- @mervinkid
- @nishuihan

Attendees:
- @shuoranliu
- @hooklee2000 

Minutes:
- ChubaoFS Hadoop Plugin repository: [chubaofs-hadoop](https://github.com/chubaofs/chubaofs-hadoop)
- Dynamic library and Java SDK (low-level API) development branch: [chubaofs:libsdk-dev](https://github.com/chubaofs/chubaofs/tree/libsdk-dev)
- Dynamic library and Java SDK (high-level API) development branch: [chubaofs:libsdk-hl-dev](https://github.com/chubaofs/chubaofs/tree/libsdk-hl-dev)
- The code and functions of `libsdk-dev` and `libsdk-hl-dev` will be integrated.

Attachments:
- [ChubaoFS Java SDK and Hadoop Plugin.pdf](https://github.com/chubaofs/chubaofs/files/5372055/ChubaoFS.Java.SDK.and.Hadoop.Plugin.pdf)

### 2020/09/22
Topic:
- Community update

Speaker:
- @mervinkid

Attendees:
- @shuoranliu

Minutes:
- ChubaoFS `v2.2.2` released. For detail see PR[#939](https://github.com/chubaofs/chubaofs/pull/939).
- ChubaoFS CSI `v2.2.2.110.0` for ChubaoFS `v2.2.2` and CSI `v1.1.0` will be released before Oct 1, 2020.
- ChubaoFS CSI `v2.2.2.030.0` for ChubaoFS `v2.2.2` and CSI `v0.3.0` will be released before Oct 1, 2020.
- ChubaoFS Helm `v2.2.2.110.0` for ChubaoFS `v2.2.2`, CSI `v1.1.0` and Helm 3 will be released before Oct 1, 2020.
- ChubaoFS Helm `v2.2.2.030.0` for ChubaoFS `v2.2.2`, CSI `v0.3.0` and Helm 3 will be released before Oct 1, 2020.

Attachements:
- [ChubaoFS Community Meeting 2020-09-22.pdf](https://github.com/chubaofs/chubaofs/files/5274095/ChubaoFS.Community.Meeting.2020-09-22.pdf)

***

### 2020/09/08
Topic:
- Community update.
- Introducing data partition selector.(PR[#853](https://github.com/chubaofs/chubaofs/pull/853)) - by @yinlei-jinan
- Discussion on feature request for automatic expanding of volume capacity.

Speaker:
- @mervinkid
- @yinlei-jinan

Attendees:
- @shuoranliu
- @Vivian7755
- @awzhgw
- @hooklee2000 

Minutes:

- Accept the feature request that automatic expanding of volume capacity.

Attachments:

- [Meeting Record](https://zoom.com.cn/rec/share/H33yQk9iLnUpQ65eBOrbw73OmrnnbCDCHcc81cgwABVw1Ea59ZV0GrRHRXkGeFc.-YyxwDuc6En1tRX_?startTime=1599568863000)
- [ChubaoFS Community Meeting 2020-09-08.pdf](https://github.com/chubaofs/chubaofs/files/5192669/ChubaoFS.Community.Meeting.2020-09-08.pdf)
- [Introduce Datapartition Selector.pdf](https://github.com/chubaofs/chubaofs/files/5192678/Introduce.Datapartition.Selector.pdf)

***

### 2020/09/01

Topic:
- Community update.
- Spark Shuffle on ChubaoFS Discussion - by @zhuzhengyi
- ChubaoFS Java SDK Discussion - by @shuoranliu

Speaker:
- @mervinkid
- @zhuzhengyi

Attendees:
- @shuoranliu
- @Vivian7755
- @hooklee2000 

Minutes:
- Consider optimizing the write logic of shuffle in the Spark plugin

Attachments: 
- [Meeting Record](https://zoom.com.cn/rec/share/nEabSJWRxn1RV-aFA8_uHwYH411nynvYW5oGh77KgvaKznMwA9qjILPMY7JSf22h.aWZToRwEsINDOIDz?startTime=1598965131000)
- [Presentation - ChubaoFS Community Meeting 2020-09-01](https://github.com/chubaofs/chubaofs/files/5165754/ChubaoFS.Community.Meeting.2020-09-01.pdf)
- [Presentation - ChubaoFS Spark Shuffle](https://github.com/chubaofs/chubaofs/files/5165848/ChubaoFS.Spark.Shuffle.Research.pdf)

***

### 2020/08/25

Topic:
- Community update

Speaker: 
- @mervinkid

Attendees: 
- @awzhgw
- @shuoranliu
- @Vivian7755
- @hooklee2000 

Minutes:
- Every community meeting announces the schedule and topic of the meeting 3 to 7 days in advance.

- Community meetings mainly include the following three forms of content:
  - Community update
  - Project design details sharing
  - Feature design discussion

- Publicize the functions under development in the form of Issue, PR, or code branch to improve the efficiency of community collaboration.

- Increase the development priority of **Spark Shuffle on ChubaoFS**. The JD.com team discloses the current design and code, and community contributors collaborate to complete the development of this feature.

Attachements:
- [Meeting Record](https://zoom.com.cn/rec/share/7tBXHbjU91tOXYnptlDVf_QqJ8e7aaa80yYbrvsLzE6n2rYACfmybVlE-otSmjIE?startTime=1598359513000)
- [Presentation - ChubaoFS Community Meeting 2020-08-25](https://github.com/chubaofs/chubaofs/files/5144711/ChubaoFS.Community.Meeting.2020-8-25.pdf)