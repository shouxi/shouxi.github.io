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

I am an Associate Professor with the [School of Computing and Artificial Intelligence, Southwest Jiaotong University](https://scai.swjtu.edu.cn/index.html). Currently, I am working on building flexible and performance-optimized network protocols for emerging networked systems/applications like distributed machine learning. 

Prior to joining Southwest Jiaotong University, I was an engineer working on cloud storage systems at Huawei for one year. I obtained my Ph.D. degree in communication and information systems from the [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) in 2016. During my PhD, I also spent one year at ETH Zurich working with [Prof. Laurent Vanbever](https://vanbever.eu/). Before that, I earned my bachelor's degree in communication engineering from the [University of Electronic Science and Technology of China](https://en.uestc.edu.cn/) in 2011. 

To contact me, drop me an email at <span id="_eml" class="gl-eml">what at what </span>.


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


### Selected Publications [[DBLP](https://dblp.org/pid/151/6230.html), [Google Scholar](https://scholar.google.com/citations?user=AGtVxDcAAAAJ), [ResearchGate](https://www.researchgate.net/profile/Shouxi_Luo)]

```blog-bib


@ARTICLE{tmc25-inp,
  author   = {Shouxi Luo and Peidong Zhang and Xin Song and Pingzhi Fan and Huanlai Xing and Long Luo and Hongfang Yu},
  title    = {Domain-Speciﬁc Transport Protocols for In-Network Processing at the Edge: A Case Study of Accelerating Model Synchronization},
  journal={IEEE Transactions on Mobile Computing},
  year={2025},

  biosite_url = {./publications/tmc25-inp.pdf},
  biosite_venue = {IEEE Transactions on Mobile Computing, 2025},  
}


@ARTICLE{tsc24-selmcast,
  author   = {Shouxi Luo and Pingzhi Fan and Ke Li and Huanlai Xing and Long Luo and Hongfang Yu},
  title    = {Efficient Parameter Synchronization for Peer-to-Peer Distributed Learning With Selective Multicast},
  journal={IEEE Transactions on Services Computing},
  year={2025},

  biosite_url = {./publications/tsc24-selmcast.pdf},
  biosite_venue = {IEEE Transactions on Services Computing, 2025},  
}

@ARTICLE{ton24-aro,
  author   = {Shouxi Luo and Xiaoyu Yu and Ke Li and Huanlai Xing},
  title    = {Releasing the Power of In-Network Aggregation With Aggregator-Aware Routing Optimization},
  journal={IEEE/ACM Transactions on Networking},
  year={2024},

  biosite_url = {./publications/ton24-aro.pdf},
  biosite_venue = {IEEE/ACM Transactions on Networking, 2024},  
}

@ARTICLE{tpds24-crew,
  author   = {Shouxi Luo and Renyi Wang and Ke Li and Huanlai Xing},
  title    = {Efficient Cross-Cloud Partial Reduce With CREW},
  journal={IEEE Transactions on Parallel and Distributed Systems},
  year={2024},

  biosite_url = {./publications/tpds24-crew.pdf},
  biosite_venue = {IEEE Transactions on Parallel and Distributed Systems, 2024},  
}


@ARTICLE{tnse24-mtree,
  author={Luo, Shouxi and Wang, Renyi and Xing, Huanlai},
  journal={IEEE Transactions on Network Science and Engineering}, 
  title={Efficient Inter-Datacenter AllReduce With Multiple Trees}, 
  year={2024},
  volume={},
  number={},
  pages={1-14},
  keywords={Training;Vegetation;Synchronization;Data models;Wide area networks;Tensors;Peer-to-peer computing;AllReduce;Inter-DC WAN;Communication Optimization},
  doi={10.1109/TNSE.2024.3419030},

  biosite_url = {./publications/tnse24-mtree.pdf},
  biosite_venue = {IEEE Transactions on Network Science and Engineering, 2024},  
}

@ARTICLE{sj24-bfgp,
  author={Luo, Shouxi and Li, Ke and Xing, Huanlai and Fan, Pingzhi},
  journal={IEEE Systems Journal}, 
  title={Efficient and Flexible Component Placement for Serverless Computing}, 
  year={2024},
  volume={18},
  number={2},
  pages={1104-1114},
  keywords={Costs;Containers;Cloud computing;Energy conservation;Serverless computing;Delays;Production;Cloud;energy saving;load balance;serverless;service placement},
  doi={10.1109/JSYST.2024.3381590},

  biosite_url = {./publications/sj24-bfgp.pdf},
  biosite_venue = {IEEE Systems Journal, 2024},  
}

@ARTICLE{ton22-poco,
  author={Luo, Shouxi and Fan, Pingzhi and Xing, Huanlai and Yu, Hongfang},
  journal={IEEE/ACM Transactions on Networking}, 
  title={Meeting Coflow Deadlines in Data Center Networks With Policy-Based Selective Completion}, 
  year={2023},
  volume={31},
  number={1},
  pages={178-191},
  keywords={Schedules;Task analysis;Bandwidth;Servers;Data communication;Data centers;Admission control;Coflow;data center networks;flow scheduling},
  doi={10.1109/TNET.2022.3187821},

  biosite_url = {./publications/ton22-poco.pdf},
  biosite_venue = {IEEE/ACM Transactions on Networking, 2022},  
}

@inproceedings{icc22-inp,
  author={Shouxi Luo and Pingzhi Fan and Huanlai Xing and Long Luo and Hongfang Yu},
  booktitle={IEEE ICC}, 
  title={Eliminating Communication Bottlenecks in Cross-Device Federated Learning with In-Network Processing at the Edge}, 
  year={2022},
  biosite_url = {./publications/icc22-inp.pdf},
  biosite_venue = {Proc. of IEEE ICC, 2022},  
}

@inproceedings {icc22-pcast,
  author = {Shouxi Luo and Pingzhi Fan and Ke Li and Huanlai Xing and Long Luo and Hongfang Yu},
  title = {Fast Parameter Synchronization for Distributed Learning with Selective Multicast},
  booktitle = {IEEE ICC},
  year = {2022},
  biosite_url = {./publications/icc22-pcast.pdf},
  biosite_venue = {Proc. of IEEE ICC, 2022},  
}

@ARTICLE{mnet21-sdm,
  author   = {Shouxi Luo and Huanlai Xing and Pingzhi Fan},
  title    = {Softwarized IP Multicast in the Cloud},
  journal={IEEE Network},
  year={2021},

  biosite_url = {./publications/mnet21-sdm.pdf},
  biosite_venue = {IEEE Network, 2021},  
}

@ARTICLE{jsac20-pam,
  author   = {Shouxi Luo and Hongfang Yu and Ke Li and Huanlai Xing},
  title    = {Efficient File Dissemination in Data Center Networks with Priority-based Adaptive Multicast},
  journal={IEEE Journal on Selected Areas in Communications},
  year={2020},

  biosite_url = {./publications/jsac20-pam.pdf},
  biosite_venue = {IEEE Journal on Selected Areas in Communications, 2020},  
}

@ARTICLE{iotj20-ppush,
  author   = {Shouxi Luo and Tie Ma and Wei Shan and Pingzhi Fan and Huanlai Xing and Hongfang Yu},
  title    = {Efficient Multisource Data Delivery in Edge Cloud With Rateless Parallel Push},
  journal={IEEE Internet of Things Journal},
  year={2020},

  biosite_url = {./publications/jiot20-ppush.pdf},
  biosite_venue = {IEEE Internet of Things Journal, 2020},  
}

@inproceedings{icpp20-poco,
  author   = {Shouxi Luo and Pingzhi Fan and Huanlai Xing and Hongfang Yu},
  title    = {Selective Coflow Completion for Time-sensitive Distributed Applications with Poco},
  booktitle={49th International Conference on Parallel Processing - ICPP},
  year={2020},

  biosite_url = {./publications/icpp20-poco.pdf},
  biosite_venue = {Proc. of 49th ICPP, 2020},  
}

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

  biosite_url = {./publications/jsyst19-msctree.pdf},
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
  biosite_venue = {Proc. of SOSR, 2017},
}

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

@INPROCEEDINGS{ifipnetworking16-cup,
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

@ARTICLE{cc14-vdc,
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
  biosite_url = {https://ieeexplore.ieee.org/document/6895393/},
  biosite_venue = {China Communications, 2014},
}

@INPROCEEDINGS{icccn14-aggr,
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

```


<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?0af3d206738f8c32cc292a5d98ee7c9c";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>
