# executebaftera
azkaban先执行A工作流，再执行B工作流

检查今天有没有跑A工作流，如果已经跑了工作流A，则自动调起工作流B，如果没跑工作流A，则将’A工作流还没跑，暂时不能执行B工作流‘发送到企业微信里面去
