# Security Bulletin: Cúram Social Program Management may be affected by Denial of Service vulnerability in Google Gson (217225)

## Security Bulletin

### Summary

IBM Cúram Social Program Management uses the Google Gson libraries, for which there is a publicly known vulnerability.
For this vulnerability, Gson is vulnerable to a denial of service caused by the deserialization of untrusted data. By using the `writeReplace()` method, a remote attacker could exploit this vulnerability to cause a denial of service.

### Vulnerability Details

IBM X-Force ID:   217225

Description:   Gson is vulnerable to a denial of service, caused by the deserialization of untrusted data.
By using the writeReplace() method, a remote attacker could exploit this vulnerability to cause a denial of service.

CVSS Base score: 7.7

CVSS Temporal Score: See: [https://exchange.xforce.ibmcloud.com/vulnerabilities/217225](https://exchange.xforce.ibmcloud.com/vulnerabilities/217225) for the current score.

CVSS Vector: (CVSS:3.0/AV:N/AC:H/PR:N/UI:N/S:U/C:L/I:H/A:H)

**Note:** The CVSS Environment Score is customer environment specific and will ultimately impact the Overall CVSS Score.
Customers can evaluate the impact of this vulnerability in their environments by accessing the links in the _References_ section of this Security Bulletin.

### Affected Products and Versions

|Affected Products|Versions|
|-----------------|---------|
|IBM Cúram Social Program Management|8.0.1|
|IBM Cúram Social Program Management|7.0.11|

### Remediation/Fixes

|Product|VRMF|Remediation/First Fix|
|-------|----|---------------------|
|IBM Cúram Social Program Management|8.0.1|Upgrade to 8.0.1_iFix3 or a subsequent 8.0.1 release.|
|IBM Cúram Social Program Management|7.0.11|Upgrade to 7.0.11_iFix7 or a subsequent 7.0.11 release.|

### Workarounds and Mitigations

None

#### Get Notified about Future Security Bulletins

Subscribe to My Notifications to be notified of important product support alerts like this.

#### References

[Complete CVSS v3 Guide](http://www.first.org/cvss/user-guide)

[On-line Calculator v3](http://www.first.org/cvss/calculator/3.0)

#### Related Information

[IBM Secure Engineering Web Portal](http://www.ibm.com/security/secure-engineering/bulletins.html)

[IBM Product Security Incident Response Blog](http://www.ibm.com/blogs/psirt)

#### Change History

08 Apr 2022: Initial Publication

According to the Forum of Incident Response and Security Teams (FIRST), the Common Vulnerability Scoring System (CVSS) is an "industry open standard designed to convey vulnerability severity and help to determine urgency and priority of response." IBM PROVIDES THE CVSS SCORES ""AS IS"" WITHOUT WARRANTY OF ANY KIND, INCLUDING THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. CUSTOMERS ARE RESPONSIBLE FOR ASSESSING THE IMPACT OF ANY ACTUAL OR POTENTIAL SECURITY VULNERABILITY.
