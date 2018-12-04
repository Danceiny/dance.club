# dance.club
The DANCE cloud
## Vision

To build `the Dance.club`, from the low-level of docker container to high-level of API.

Technically, I'll try different languages like golang/java/python/js, and concepts that k8s, ERA, data analysis (basic analysis && machine learning && deep learning) also included.
## Roadmap

| Component | Nickname| Language | Main Dependency | Schedule|
| --------- | ----- | -------- | --- |---|
| Broker    | pigeon       | golang   | [gocelery](https://github.com/Danceiny/gocelery)                                                | 基本功能已完成开发，后续在联调中改进，预留7个工作日                       |
| Container | [marxist](https://github.com/Danceiny/Marxist)    | golang   | -                                                  | 参考《自己动手写Docker》先实现一个低端docker，预计7个工作日；完成基础联调后，尝试接入k8s，预计7个工作日 |
| Web       | [kaynes](https://github.com/Danceiny/kaynes)      | java     | [sprin cloud](https://spring.io)                                                                | 基础联调的入口，定义好各种API，参考CodingHub/russell-cloud等，预计4个工作日                                          |
| Cli       | box | nodejs   | [教程](https://medium.freecodecamp.org/writing-command-line-applications-in-nodejs-2cf8327eee2) | 最后考虑实现，暂时用postman等http客户端替代                               |
| Data| [khaki](https://github.com/Danceiny/khaki)| python |pandas | 基础联调后，尝试接入实验数据并清洗| 

原CodingHub、CodingHub-Cli、CodingHub-Web等三个项目，在完成上述工作后，再视情况更新。