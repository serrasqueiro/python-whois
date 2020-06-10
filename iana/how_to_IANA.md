# TLD - Top Level Domain

IANA handles TLD and ccTLD (Country Top Level Domain).
To get latest list, use:
% curl http://data.iana.org/TLD/tlds-alpha-by-domain.txt -o tlds_alpha.txt
See [IANA Root Files](https://www.iana.org/domains/root/files).

To compare old files, do:
% diff -y -W 80 domains.txt tlds_alpha.txt | grep -v "XN-"

## ccTLD

A Country TLD has a delegation record controlled by IANA.
Example, [.PT](https://www.iana.org/domains/root/db/pt.html)

WIPO (World Intelectual Property Organization), at [wipo](http://wipo.int) manages disputes accross the world countries.
It updates the IANA agreements, example [here](https://www.wipo.int/amc/en/domains/cctld_db/codes/pt.html)
You can find each country individually here: [ccTLD Database](https://www.wipo.int/amc/en/domains/cctld_db/)

Primary choice for the two letters are alpha-2 code (2 letters) from ISO-3361.
The listing is comprehensively here:
	https://github.com/serrasqueiro/wateriso/blob/master/docs/country/ISO_3361_list.txt
