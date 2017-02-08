# AlwaysOn

Note: We are currently revising our code base to protect the anonymity of a
paper currently under submission. Our commit history originally included the
names of authors on the paper. Furthermore, our code base had references to
tools that revealed the name of our lab and institution. We have currently
removed this history and files to avoid breaking the double-blind nature of the
review process. We are working on modifying this code base to remove 
these references.

Over the last decade, broadband access speeds have continuously increased,
spurred by both government and private investment in infrastructure. Such
investments are motivated by the recognized social and economical benefits of
connectivity. While providing access and sufficient capacity still remains a
challenge in many parts of the world, in most developed countries, broadband
providers are offering sufficiently high capacities (i.e., above 10~Mbps) to
encourage consumers to migrate services for entertainment, communication and
home monitoring to over-the-top (OTT) alternatives. According to a recent
survey, nearly 60% of US broadband households subscribe to an OTT video
service. This has begun to impact pay-television providers with an estimated
loss of approximately 1.4 million customers "cutting the cord" in 2014.

Motivated by these findings we developed a system called "AlwaysOn" which uses
MultiPath TCP (MPTCP) to leverage the fact that most broadband users are
potentially within range of a number of additional Access Points (APs), whether
they be APs set up by their neighbors, or the ability to use a 4G-enabled
device as a Wi-Fi hotspot. Instructions for creating an AlwaysOn gateway
will be available under ``gateway''. 

This code base also includes the scripts and libraries used to analyze
the data made publicly available by the FCC. These tools and scripts
will be available under the ``analysis'' directory.

