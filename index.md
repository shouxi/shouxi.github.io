```bio-remove
Steps of using this template:

1. Write a code block with the language "bio-meta" to set up metadata.
2. Use a heading (level 1) with "#" to set the heading. Use this only once.
3. Write Markdown as usual with these extensions:
  - To add comments that are not printed, write a code block with the language "bio-remove".
  - To protect an excerpt so that it's printed as-is, write <!--[bio][protect]your content here[bio]-->.
  - To write a math equation, write `math:\LaTeX` or `display:\LaTeX`.
  - To include a list of papers, put the BibTeX citations in the order you want it to appear in a code block with the language "blog-bib".
4. Run "build.sh" or "build.bat" or "build.js" to compile.

NOTE that this README.md is not licensed under the MIT license. You can use this as a reference or template, but not use (the specific content of) this file (relating to the original author).
```

```bio-meta
{
    "name": "Shouxi Luo",
    "title": "Shouxi Luo | Homepage",
    "description": "Shouxi Luo&#8217;s Homepage.",
    "domain": "shouxi.name",
    "date-created": "2020-02-11",
    "repo": "https://github.com/to-be-added"
}
```

# Shouxi Luo <!--span aria-hidden="true"> (</span><span lang="zh-CN">xx</span><span aria-hidden="true">)</span-->

<!--figure class="gl-page-background gl-float-right" style="text-align: center;"><img src="./assets/images/hero-image.png" alt="A photo of Shouxi Luo" width="160" height="160" style="max-width: 160px;" /></figure-->

I am a Lecturer with the [School of Information Science and Technology, Southwest Jiaotong University](http://sist.swjtu.edu.cn/indexEn.do?action=index). Currently, I am working on building flexible and performance-optimized network protocols for emerging networked systems/applications like distributed machine learning and serverless computing. 

Prior to joining Southwest Jiaotong University, I was an engineer working on cloud storage systems at Huawei for one year. I obtained my Ph.D. degree in communication and information system from [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) in 2016. During my PhD, I also spent one year at ETH Zurich working with [Prof. Laurent Vanbever](https://vanbever.eu/). Before that, I earned my bachelor's degree in communication engineering from the [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) in 2011. 

To contact me, drop me an email at <span id="_eml" class="gl-eml">what at what </span>.

[Google Scholar](https://scholar.google.com/citations?user=AGtVxDcAAAAJ), [ResearchGate](https://www.researchgate.net/profile/Shouxi_Luo)

<!--[bio][protect]
<script type="application/javascript">
window.setTimeout(function ()
{
var u = [98, 23, 62, 23, 83, 1, 120, 27, 46, 22, 48, 112, 97, 69, 64, 79, 59, 28];
var v = [17, 111, 82, 98, 60, 65, 11, 108, 68, 98, 69, 94, 4, 33, 53, 97, 88, 114];
var addr = [];
for (var i = 0; i < u.length; ++i)
{
addr.push(String.fromCharCode(u[i] ^ v[i]));
}
addr = addr.join('');
var tgt = document.getElementById('_eml');
tgt.innerHTML = '<a href="mailto:' + addr + '">' + addr + '</a>';
tgt.removeAttribute('class');
}, 600);
</script>
[bio]-->


## Publications


### 2020

```blog-bib

@ARTICLE{jsac20-pam,
  author   = {Shouxi Luo and Hongfang Yu and Ke Li and Huanlai Xing},
  title    = {Efficient File Dissemination in Data Center Networks with Priority-based Adaptive Multicast},
  journal={IEEE Journal on Selected Areas in Communications},
  year={2020},

  biosite_url = {./publications/jsac20-pam.pdf},
  biosite_venue = {IEEE Journal on Selected Areas in Communications, 2020},  
}

@ARTICLE{jnca20-jpas,
  author   = {Pan Zhou and Xinshu He and Shouxi Luo and Hongfang Yu and Gang Sun},
  title    = {JPAS: Job-progress-aware flow scheduling for deep learning clusters},
  journal={IEEE Journal on Selected Areas in Communications},
  year={2020},

  biosite_venue = {Journal of Network and Computer Applications, 2020},  
}

@article{fgcs20-psnet,
  title = "PSNet: Reconfigurable network topology design for accelerating parameter server architecture based distributed machine learning",
  journal = "Future Generation Computer Systems",
  volume = "106",
  pages = "320 - 332",
  year = "2020",
  issn = "0167-739X",
  doi = "https://doi.org/10.1016/j.future.2020.01.004",
  url = "http://www.sciencedirect.com/science/article/pii/S0167739X19315614",
  author = "Ling Liu and Qixuan Jin and Dan Wang and Hongfang Yu and Gang Sun and Shouxi Luo",

  biosite_venue = {Future Generation Computer Systems, 2020}, 
}


@INPROCEEDINGS{7996840,
  author={Juan Chen and Zhiwen Xiao and Huanlai Xing and Penglin Dai and Shouxi Luo and Muhammmad Iqbal},
  booktitle={2017 IEEE International Conference on Communications (ICC)},
  title={STDPG: A Spatio-Temporal Deterministic Policy Gradient Agent for Dynamic Routing in SDN},
  year={2020},
  month={May},

  biosite_venue = {Proc. of IEEE ICC, 2020},
}
```

### 2019
```blog-bib

@ARTICLE{ieeesj19-msctree,
  author={Shouxi {Luo} and Huanlai {Xing} and Ke {Li}},
  journal={IEEE Systems Journal},
  title={Near-Optimal Multicast Tree Construction in Leaf-Spine Data Center Networks},
  year={2019},
  volume={},
  number={},
  pages={1-4},
  doi={10.1109/JSYST.2019.2918446},
  ISSN={2373-7816},
  month={},

  biosite_url = {./publications/ieeesj19-dcn-multicast-tree.pdf},
  biosite_venue = {IEEE Systems Journal, 2019},  
}

@article{jnca19-cup,
  title = "Customizable network update planning in SDN",
  journal = "Journal of Network and Computer Applications",
  volume = "141",
  pages = "104 - 115",
  year = "2019",
  issn = "1084-8045",
  doi = "https://doi.org/10.1016/j.jnca.2019.05.007",
  url = "http://www.sciencedirect.com/science/article/pii/S1084804519301675",
  author = "Shouxi Luo and Hongfang Yu and Long Luo and Lemin Li",

  biosite_url = {./publications/jnca19-cup.pdf},
  biosite_venue = {Journal of Network and Computer Applications, 2019},  
}


@article{jnca19-paco,
  title = "Scalable explicit path control in software-defined networks",
  journal = "Journal of Network and Computer Applications",
  volume = "141",
  pages = "86 - 103",
  year = "2019",
  issn = "1084-8045",
  doi = "https://doi.org/10.1016/j.jnca.2019.05.014",
  url = "http://www.sciencedirect.com/science/article/pii/S108480451930181X",
  author = "Long Luo and Hongfang Yu and Shouxi Luo and Zilong Ye and Xiaojiang Du and Mohsen Guizani",

  biosite_venue = {Journal of Network and Computer Applications, 2019},  
}

@article{XING2019575,
  title = "An integer encoding grey wolf optimizer for virtual network function placement",
  journal = "Applied Soft Computing",
  volume = "76",
  pages = "575 - 594",
  year = "2019",
  issn = "1568-4946",
  doi = "https://doi.org/10.1016/j.asoc.2018.12.037",
  url = "http://www.sciencedirect.com/science/article/pii/S1568494619300018",
  author = "Huanlai Xing and Xinyu Zhou and Xinhan Wang and Shouxi Luo and Penglin Dai and Ke Li and Hui Yang",

  biosite_venue = {Applied Soft Computing, 2019},  
}

@article{clustercomputing19-fecn,
  title = "Flow-aware explicit congestion notification for datacenter networks",
  journal = "Cluster Computing",
  volume = "22",
  year = "2019",
  author = "Pan Zhou and Hongfang Yu and Gang Sun and Long Luo and Shouxi Luo and Zilong Ye",

  biosite_venue = {Cluster Computing, 2019},  
}

@inproceedings{10.1145/3321408.3323088,
  author = {Xing, Huanlai and Li, Song and Dai, Penglin and Luo, Shouxi and Li, Ke and Yang, Hui},
  title = {A PBIL for Delay Constrained Virtual Network Function Placement with Load Balancing},
  year = {2019},
  isbn = {9781450371582},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3321408.3323088},
  doi = {10.1145/3321408.3323088},
  booktitle = {Proceedings of the ACM Turing Celebration Conference - China},
  articleno = {Article 7},
  numpages = {6},
  location = {Chengdu, China},
  series = {ACM TURC'19},

  biosite_venue = {Proc. of the ACM Turing Celebration Conference - China, 2019},  
}


@article{Chen_2019, 
  title={MonLink: Piggyback Status Monitoring over LLDP in Software-Defined Energy Internet}, 
  volume={12}, 
  ISSN={1996-1073}, 
  url={http://dx.doi.org/10.3390/en12061147}, 
  DOI={10.3390/en12061147}, 
  number={6}, 
  journal={Energies}, 
  publisher={MDPI AG}, 
  author={Chen, Xi and Chen, Yue and Sangaiah, Arun and Luo, Shouxi and Yu, Hongfang}, 
  year={2019}, 
  month={Mar}, 
  pages={1147},

  biosite_venue = {Energies, 2019},  
}

```

### 2017
```blog-bib

@InProceedings{sosr17-swingstate,
  author     = {Luo, Shouxi and Yu, Hongfang and Vanbever, Laurent},
  title      = {Swing State: Consistent Updates for Stateful and Programmable Data Planes},
  booktitle  = {Symposium on SDN Research},
  year       = {2017},
  series     = {SOSR '17},
  pages      = {115--121},
  acmid      = {3050233},
  address   = {New York, NY, USA},
  doi        = {10.1145/3050220.3050233},
  isbn       = {978-1-4503-4947-5},
  keywords   = {Network updates, P4, Software-Defined Networking, Stateful programmable data planes},
  location   = {Santa Clara, CA, USA},
  numpages   = {7},
  publisher = {ACM},
  url       = {http://doi.acm.org/10.1145/3050220.3050233},

  biosite_url = {./publications/sosr17-swingstate.pdf},
  biosite_venue = {Proc. of Symposium on SDN Research (SOSR), 2017},
}

@INPROCEEDINGS{8117587,
  author={Yangming {Zhao} and Shouxi {Luo} and Yi {Wang} and Sheng {Wang}},
  booktitle={2017 IEEE 25th International Conference on Network Protocols (ICNP)},
  title={Cotask scheduling in cloud computing},
  year={2017},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ICNP.2017.8117587},
  ISSN={null},
  month={Oct},

  biosite_venue = {Proc. of 25th ICNP, 2017},
}

@INPROCEEDINGS{8116412,
  author={Long {Luo} and Hongfang {Yu} and Shouxi {Luo}},
  booktitle={2017 IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS)},
  title={Scalable path provision in software defined networks},
  year={2017},
  volume={},
  number={},
  pages={414-419},
  keywords={computer network performance evaluation;delays;routing protocols;software defined networking;telecommunication traffic;scalable path provision;software defined networks;network performance;flexible routing paths;hop-by-hop;scalability issue;flow table overhead;path setup delay;large-scale networks;PACO;path information;packet header;network edges;heavy header overhead;path flexibility;leverage SR;desired path;on-demand paths;minimum header overhead;OpenFlow-SDN solutions;state-of-art SR-SDN solution;negligible header overhead;source routing;Conferences;Scalability;Routing;Software;Delays;Control systems;Quality of service},
  doi={10.1109/INFCOMW.2017.8116412},
  ISSN={null},
  month={May},

  biosite_venue = {Proc. of INFOCOM WKSHPS, 2017},
}

@INPROCEEDINGS{7996840,
  author={Weiran {Ding} and Hongfang {Yu} and Shouxi {Luo}},
  booktitle={2017 IEEE International Conference on Communications (ICC)},
  title={Enhancing the reliability of services in NFV with the cost-efficient redundancy scheme},
  year={2017},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ICC.2017.7996840},
  ISSN={1938-1883},
  month={May},

  biosite_venue = {Proc. of IEEE ICC, 2017},
}


```

### 2016
```blog-bib

@Article{tpds16-dcas,
  author   = {Shouxi Luo and Hongfang Yu and Yangming Zhao and Sheng Wang and Shui Yu and Lemin Li},
  title    = {Towards Practical and Near-Optimal Coflow Scheduling for Data Center Networks},
  journal  = {IEEE Transactions on Parallel and Distributed Systems},
  year     = {2016},
  volume   = {27},
  number   = {11},
  pages    = {3366-3380},
  month    = {Nov},
  doi      = {10.1109/TPDS.2016.2525767},
  issn     = {1045-9219},

  biosite_url = {./publications/tpds16-dcas-updated.pdf},
  biosite_venue = {IEEE Transactions on Parallel and Distributed Systems, 2016},
}

@INPROCEEDINGS{7497214,
  author={Shouxi {Luo} and Hongfang {Yu} and Long {Luo} and Lemin {Li}},
  booktitle={2016 IFIP Networking Conference (IFIP Networking) and Workshops},
  title={Arrange your network updates as you wish},
  year={2016},
  volume={},
  number={},
  pages={10-18},
  keywords={linear programming;software defined networking;updating network configuration;SDN;update process;in-flight packet;misusing rule;transient throughput loss management;update deadline;CUP;customizable update planner;generic linear programming model;update planning problem;Mininet;Planning;Throughput;Transient analysis;System recovery;Linear programming;Optimization;Control systems},
  doi={10.1109/IFIPNetworking.2016.7497214},
  ISSN={null},
  month={May},

  biosite_url = {./publications/ifipnetworking16-cup.pdf},
  biosite_venue = {Proc. of 15th IFIP Networking, 2016 (Best paper award)},
}

@InProceedings{icc16-d2cas,
  author    = {Shouxi Luo and Hongfang Yu and Lemin Li},
  title     = {Decentralized deadline-aware coflow scheduling for datacenter networks},
  booktitle = {IEEE ICC},
  year      = {2016},
  pages     = {1-6},
  month     = {May},
  doi       = {10.1109/ICC.2016.7511251},
  issn      = {1938-1883},

  biosite_url = {./publications/icc16-d2cas.pdf},
  biosite_venue = {Proc. of IEEE ICC, 2016},
}


@INPROCEEDINGS{7841562,
  author={Long {Luo} and Hongfang {Yu} and Shouxi {Luo} and Mingui {Zhang} and Shui {Yu}},
  booktitle={2016 IEEE Global Communications Conference (GLOBECOM)},
  title={Achieving Fast and Lightweight SDN Updates with Segment Routing},
  year={2016},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/GLOCOM.2016.7841562},
  ISSN={null},
  month={Dec},

  biosite_venue = {Proc. of IEEE GLOBECOM, 2016},
}


@INPROCEEDINGS{7841769,
  author={Yuanxiang {Gao} and Hongfang {Yu} and Shouxi {Luo} and Shui {Yu}},
  booktitle={2016 IEEE Global Communications Conference (GLOBECOM)},
  title={Efficient and Low-Delay Task Scheduling for Big Data Clusters in a Theoretical Perspective},
  year={2016},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/GLOCOM.2016.7841769},
  ISSN={null},
  month={Dec},

  biosite_venue = {Proc. of IEEE GLOBECOM, 2016},
}


@INPROCEEDINGS{7511241,
  author={Yuanxiang {Gao} and Hongfang {Yu} and Shouxi {Luo} and Shui {Yu}},
  booktitle={2016 IEEE International Conference on Communications (ICC)},
  title={Information-agnostic coflow scheduling with optimal demotion thresholds},
  year={2016},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ICC.2016.7511241},
  ISSN={1938-1883},
  month={May},

  biosite_venue = {Proc. of IEEE ICC, 2016},
}

```

### 2015
```blog-bib

@article{comnet15-ftagg,
  title = "Practical flow table aggregation in SDN",
  journal = "Computer Networks",
  volume = "92",
  pages = "72 - 88",
  year = "2015",
  issn = "1389-1286",
  doi = "https://doi.org/10.1016/j.comnet.2015.09.016",
  url = "http://www.sciencedirect.com/science/article/pii/S1389128615003278",
  author = "Shouxi Luo and Hongfang Yu and Lemin Li",

  biosite_url = {./publications/comnet15-ftagg.pdf},
  biosite_venue = {Computer Networks, 2015},

}

@ARTICLE{cl15-two-phase-update,
  author={Shouxi {Luo} and Hongfang {Yu} and Lemin {Li}},
  journal={IEEE Communications Letters},
  title={Consistency is Not Easy: How to Use Two-Phase Update for Wildcard Rules?},
  year={2015},
  volume={19},
  number={3},
  pages={347-350},
  doi={10.1109/LCOMM.2015.2388754},
  ISSN={2373-7891},
  month={March},

  biosite_url = {./publications/cl15-two-phase-update.pdf},
  biosite_venue = {IEEE Communications Letters, 2015},
}

@InProceedings{icc15-dcas,
  author    = {Shouxi Luo and Hongfang Yu and Yangming Zhao and Bin Wu and Sheng Wang and Lemin Li},
  title     = {Minimizing average coflow completion time with decentralized scheduling},
  booktitle = {2015 IEEE International Conference on Communications (ICC)},
  year      = {2015},
  pages     = {307-312},
  month     = {June},
  doi       = {10.1109/ICC.2015.7248339},
  issn      = {1550-3607},

  biosite_url = {./publications/icc15-dcas.pdf},
  biosite_venue = {Proc. of IEEE ICC, 2015},
}

@ARTICLE{7174945,
  author={Yangming {Zhao} and Sheng {Wang} and Shouxi {Luo} and  Vishal {Anand} and Hongfang {Yu} and Xiong {Wang} and Shizhong {Xu} and Xiaoning {Zhang}},
  journal={Journal of Lightwave Technology},
  title={Dynamic Topology Management in Optical Data Center Networks},
  year={2015},
  volume={33},
  number={19},
  pages={4050-4062},
  doi={10.1109/JLT.2015.2464079},
  ISSN={1558-2213},
  month={Oct},

  biosite_venue = {Journal of Lightwave Technology, 2015},
}


@INPROCEEDINGS{7249247,
  author={Long {Luo} and Hongfang {Yu} and Shouxi {Luo} and Mingui {Zhang}},
  booktitle={2015 IEEE International Conference on Communications (ICC)},
  title={Fast lossless traffic migration for SDN updates},
  year={2015},
  volume={},
  number={},
  pages={5803-5808},
  doi={10.1109/ICC.2015.7249247},
  ISSN={1938-1883},
  month={June},

  biosite_venue = {Proc. of IEEE ICC, 2015},
}

```

### 2014
```blog-bib


@ARTICLE{6895393,
  author={Shouxi {Luo} and Hongfang {Yu} and Lemin {Li} and Dan {Liao} and Gang {Sun}},
  journal={China Communications},
  title={Traffic-aware VDC embedding in data center: A case study of fattree},
  year={2014},
  volume={11},
  number={7},
  pages={142-152},
  doi={10.1109/CC.2014.6895393},
  ISSN={1673-5447},
  month={July},

  biosite_venue = {China Communications, 2014},
}

@INPROCEEDINGS{6911781,
  author={Shouxi {Luo} and Hongfang {Yu} and Lemin {Li}},
  booktitle={2014 23rd International Conference on Computer Communication and Networks (ICCCN)},
  title={Fast incremental flow table aggregation in SDN},
  year={2014},
  volume={},
  number={},
  pages={1-8},
  keywords={content-addressable storage;protocols;software radio;telecommunication computing;fast incremental flow table aggregation;openflow-based SDN;flow tables;TCAM-hungry;reachability failures;forwarding loops;traffic isolation;nonprefix aggregation scheme;Weaving;Merging;Aggregates;Semantics;Acceleration;Redundancy;Concrete},
  doi={10.1109/ICCCN.2014.6911781},
  ISSN={1095-2055},
  month={Aug},

  biosite_url = {./publications/icccn14-ftagg.pdf},
  biosite_venue = {Proc. of ICCCN, 2014},
}

@INPROCEEDINGS{7037142,
  author={Yangming {Zhao} and Sheng {Wang} and Shouxi {Luo} and Hongfang {Yu} and Shizhong {Xu} and Xiaoning {Zhang}},
  booktitle={2014 IEEE Global Communications Conference},
  title={Dynamic topology management in optical datacenter networks},
  year={2014},
  volume={},
  number={},
  pages={2246-2251},
  doi={10.1109/GLOCOM.2014.7037142},
  ISSN={1930-529X},
  month={Dec},

  biosite_venue = {Proc. of IEEE GLOBECOM, 2014},
}

```

<script type="text/javascript" src="http://tajs.qq.com/stats?sId=66516992" charset="UTF-8"></script>