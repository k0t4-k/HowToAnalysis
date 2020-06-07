# GoLang Analysis

Despite the Kaiji file being stripped, we were able to restore function names using IDAGolangHelper. This technique works by retrieving function definitions embedded within the Golang binary which are not removed by the strip command. 

## HowTo

- [Analyzing Golang Executables](https://www.pnfsoftware.com/blog/analyzing-golang-executables/)
- [Reversing Golang Binaries: Part-1](https://medium.com/@nishanmaharjan17/reversing-golang-binaries-part-1-c273b2ca5333) 
- [The Gopher in the Room: Analysis of GoLang Malware in the Wild](https://www.paloaltonetworks.jp/company/in-the-news/2019/the-gopher-in-the-room-analysis-of-golang-malware-in-the-wild)
- [Annotating Golang binaries with Cutter and Jupyter](https://isc.sans.edu/diary/rss/24790)
- [Hackers turn to Golang to create new malware](https://www.scmagazineuk.com/hackers-turn-golang-create-new-malware/article/1524538)
- [An Overview of the Recent Wave of Malware Written in GoLang](https://cyware.com/news/an-overview-of-the-recent-wave-of-malware-written-in-golang-fa80a815)
- [List of reverse articles](https://twitter.com/binitamshah/status/1192254101733695489)

## Malware

- [Analyzing a new stealer written in Golang](https://blog.malwarebytes.com/threat-analysis/2019/01/analyzing-new-stealer-written-golang/)
- [Go - Reverse Engineering, Malware Deep Insight](https://vk-intel.org/tag/go/)
- [Analysis of A New Golang Ransomware Targeting Linux Systems](https://www.fortinet.com/blog/threat-research/new-golang-ransomware-targeting-linux-systems.html)
- [GoBrut: A new GoLang Botnet](https://blog.yoroi.company/research/gobrut-a-new-golang-botnet/)
- [New Golang Malware is Spreading via Multiple Exploits to Mine Monero](https://www.f5.com/labs/articles/threat-intelligence/new-golang-malware-is-spreading-via-multiple-exploits-to-mine-mo)
- [Golang-based Spreader Used in a Cryptocurrency-Mining Malware Campaign](https://blog.trendmicro.com/trendlabs-security-intelligence/golang-based-spreader-used-in-a-cryptocurrency-mining-malware-campaign/)

## Tool

- [IDAGolangHelper](https://github.com/sibears/IDAGolangHelper)

