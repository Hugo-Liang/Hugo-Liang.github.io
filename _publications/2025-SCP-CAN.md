---
title: "Automatic Identification of Extrinsic Bug Reports for Just-In-Time Bug Prediction"
collection: publications
category: manuscripts
permalink: /publication/2025-SCP-CAN
excerpt: '

    • We extract bug reports from the OpenStack project and apply various text classification techniques to evaluate the effectiveness of identifying extrinsic bugs. Experimental results indicate that text classification techniques can effectively identify extrinsic bugs by analyzing bug reports. Our proposed CAN model demonstrates the best performance in terms of the F1 score.<br>

    • We examine the role of source code in identifying extrinsic bugs. We hypothesize that valuable information can be extracted from the source code present in bug reports and conduct experiments to compare the classification performance of datasets incorporating and excluding code. The experimental results indicate that datasets incorporating source code as text enhance the models' ability to identify extrinsic bugs, while excluding source code generally degrades models' performance.

'
date: 2025-08-16
venue: 'Science of Computer Programming'

paperurl: 'http://hugo-liang.github.io/files/paper1.pdf'

citation: 'Guisheng Fan, <strong>Yuguo Liang</strong>, Longfei Zu, Huiqun Yu, Zijie Huang, Wentao Chen. Automatic Identification of Extrinsic Bug Reports for Just-In-Time Bug Prediction. Science of Computer Programming 2025. [CCF-B][大修返回]
'
---

In software development, developers create bug reports within Issue Tracking System (ITS) to describe the cause, symptoms severity, and other technical details of bugs. ITS includes reports of both intrinsic bugs (i.e., those originating within the software itself) and extrinsic bugs (i.e., those arising from third-party dependencies). Although extrinsic bugs do not appear in any activities within the Version Control System (VCS), Just-In-Time (JIT) bug prediction can still leverage internal software information, such as VCS process metrics.