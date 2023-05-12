# Remote Live Forensics Using Google GRR Rapid Response

## Table of Contents

- [Introduction](#Introduction)
- [Tools Used](#Tools-Used)
- [Approach to Problem](#Approach-to-Problem)
- [Learning Outcomes](#Learning-Outcomes)
- [References](#References)

<h2 id="#Introduction">Introduction</h2>

The premise of this project is to perform live forensics on remote clients using GRR Rapid Response then forward that information to Splunk. The final report will be linked in the [References section](#References).

<h2 id="#Tools-Used">Tools Used</h2>

The tools used here are the following:

1. [Ubuntu](https://ubuntu.com/)
2. [Google GRR Rapid Response](https://github.com/google/grr)
3. [Oracle VM VirtualBox](https://www.virtualbox.org/)
4. [Splunk](https://www.splunk.com/)

<h2 id="#Approach-to-Problem">Approach to Problem</h2>

1. Hosted both a list of clients that were to be scanned by GRR and the host machine that will be doing the scanning.
2. Ran a network scan on a selected client on GRR.
3. Downloaded results as a .csv file format and forwarded to Splunk using email.
4. Used Splunk search by host and source to locate file.

<h2 id="#Learning-Outcomes">Learning Outcomes</h2>

1. Learned how to scan multiple clients using GRR and what kind of scan to initiate.
2. Learned how to determine/select the type of output for the data to be analyzed within GRR.

## References

[Written report linked here](https://github.com/JacYuan1/Remote-Live-Forensics-Using-Google-GRR-Rapid-Response-Project/blob/main/Report.pdf)
