---
layout: post
title: "Notion으로 글 작성하고 Github io로 글 옮기기"
subtitle: "[Tips]"
date: 2020-03-02 17:00
background: 
tag: [Tips, Github io, Notion]
---

# Motion recognition

Data

Class : Walk, Sit, Lay, Step up, Step down 

Collection period : 2024.05.14 ~ 2024.05.30

Number of Subject : about 10

Ingestion devices : Hicardi

Feature : ECG, Accelerometer(Multi-Modality)

![Hicardi.jpg](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/d9bd865a-07b7-4f21-8fa8-9e921330e00b.png)

Model Structure Figure

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled.png)

        Model Structure

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%201.png)

                         LSTM

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%202.png)

                  CNN

Data Split

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%203.png)

Train Report

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%204.png)

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%205.png)

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%206.png)

![Untitled](../../../Downloads/609451c9-dcca-4daa-853b-717cc46ccd68_Export-36bc3255-860e-482e-a78f-24813d8d119e/Motion%20recognition%20923ce3eddb6149d8806af21065f71b65/Untitled%207.png)