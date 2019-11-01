# Blockchain Performance Monitoring

This is the source code of the evaluation of the paper "A DETAILED AND REAL-TIME PERFORMANCE MONITORING FRAMEWORK FOR BLOCKCHAIN SYSTEMS".
With one-line command you can replay the evaluation in the paper.

We decide to move the key back-end code here instead of ibase.site for easier following. 

As for visulization, you can choose any front-end libraries as you like.


## Too Long No Read

`unzip Logs.zip` (or manually unzip Logs.zip in the directory)

`node main.js` (if you have installed node.js)


## Qucik Start

First of all, `git clone https://github.com/tczpl/BlockchainPerformanceMonitoring.git`.

And `cd BlockchainPerformanceMonitoring`.

Or download the ZIP, if you have not installed git.

### For Linux (Ubuntu 18.04)

Install unzip: `sudo apt-get install unzip`

Install nodejs: `sudo apt-get install nodejs`

Unzip the Logs files: `unzip Logs.zip`

Just run: `node main.js`

### For Windows
Please manually unzip `Logs.zip`.

Then download and install Node.js from <https://nodejs.org/>.

Just run `node main.js` in command.

## Paper
If you are interested in this work, you can refer to our paper.

[Zheng, P., Zheng, Z., Luo, X., Chen, X., & Liu, X. (2018, May). A detailed and real-time performance monitoring framework for blockchain systems. In 2018 IEEE/ACM 40th International Conference on Software Engineering: Software Engineering in Practice Track (pp. 134-143). IEEE.](http://xblock.pro/files/pl/a-detailed-and-real-time-performance-monitoring-framework-for-blockchain-systems.pdf)


@inproceedings{zheng2018detailed,
  title={A detailed and real-time performance monitoring framework for blockchain systems},
  author={Zheng, Peilin and Zheng, Zibin and Luo, Xiapu and Chen, Xiangping and Liu, Xuanzhe},
  booktitle={2018 IEEE/ACM 40th International Conference on Software Engineering: Software Engineering in Practice Track (ICSE-SEIP)},
  pages={134--143},
  year={2018},
  organization={IEEE}
}

## Dependency
We use [Netdata](https://github.com/netdata/netdata) to obtain the data of hardware resource.

Front-end: [AngularJS](https://angularjs.org/), lately upload.
