# nodejs-event-loop-blocking-demo
This repo accompanies an article. It contains small Express servers that reproduce four common causes of event loop blocking in Node.js (synchronous crypto, large JSON parsing, a ReDoS-prone regex, and CPU-bound work), plus the fixed versions and the scripts used to measure them. Every number in the article can be reproduced with the commands below.
