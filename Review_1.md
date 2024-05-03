<h2 ng-show="!currentProject.is_career" class="result-label h-slim-top ng-binding"> Requires Changes <!-- ngIf: doesNotMeetCount > 0 --><div ng-if="doesNotMeetCount > 0" class="ng-scope"> <h3 class="result-label ng-binding"><span class="failed"></span>7 specifications require changes</h3> </div><!-- end ngIf: doesNotMeetCount > 0 --> </h2> <!-- ngIf: currentProject.is_career && hasMentor --> </div><!-- end ngIf: hasFeedback && submission.result --> <!-- ngIf: submission.general_comment --><div ng-if="submission.general_comment" class="row row-gap-medium ng-scope"> <div class="col-xs-12 ng-isolate-scope" marked="submission.general_comment"><p>Hello,<br></p>
<p>🎊  Welcome to Udacity's Enterprise Security ND program 🎊<br>I noticed you have an issue due to the expired Udacity workspace session. I suggest that you use the Udacity workspace again to complete the project and keep in mind that each session of the Udacity workspace is valid for 7 hours for this project. However, this was a good starting point for this project 👍 You did a great job at providing the Securing the Perimeter report 👏🏻<br>Please make the below modifications to meet all rubric items</p>
<ol>
<li>Provide screenshots of each VM that was created in each subnet. The screenshot must show the VM detail information (IP address, Subnetwork, etc.) </li>
<li>Provide a screenshot that confirms that the Public DMZ is worldwide accessible on TCP ports 80 and 443</li>
<li>Modify the Kibana incoming traffic rules and ensure the only traffic allowed inbound to the server is from both virtual networks, and Kibana is accessible from the Internal Network.</li>
<li>Provide a screenshot that clearly displays the Filebeat service running by showing the Filebeat status is Active.</li>
<li>Provide a screenshot of the Filebeat config file showing the routing of logs to Elasticsearch</li>
<li>Provide screenshots of Denial of Service (DoS), Brute Force, and Port Scanning attack alert definitions in your report. </li>
<li>Provide the Incident Response for Denial of Service (DoS), Brute Force, and Port Scanning attack alert definitions in your report.</li>
<li>Provide a detailed comparative analysis that accurately describes the differences between a Zero Trust model and modern network architecture design. Your answer should cover at least four of the following:<ul>
<li>Difference in segmentation</li>
<li>User identification and access</li>
<li>Data security</li>
<li>The concept of trust</li>
<li>Why traditional perimeter defense is outdated due to the emergence of the cloud</li>
<li>Evolution of threat landscape.</li>
</ul>
</li>
</ol>
<h5 id="external-resources">External Resources</h5>
<ul>
<li>Using a VPN to connect to your private VPC in Azure enhances security by creating an encrypted and secure connection over the internet. This helps protect data in transit and ensures that communications between your on-premises infrastructure and Azure VPC are secure. For detailed information and guidance, you can refer to the official Azure documentation on <a href="https://learn.microsoft.com/en-us/azure/vpn-gateway/" target="_blank">VPN Gateway documentation</a>.</li>
<li><a href="https://learn.microsoft.com/en-us/azure/security/fundamentals/network-best-practices" target="_blank">This article</a> discusses a collection of Azure best practices to enhance your network security. These best practices are derived from our experience with Azure networking and the experiences of customers like yourself.</li>
<li>Continuous monitoring with a Security Information and Event Management (SIEM) solution in Azure is essential for maintaining a proactive and effective security posture. SIEM helps you centralize and analyze security data from various sources, enabling early detection of potential security threats and providing valuable insights into the security status of your Azure environment. For detailed information and guidance, you can refer to the official Azure documentation on <a href="https://learn.microsoft.com/en-us/azure/defender-for-cloud/" target="_blank">Azure Security Center</a></li>
<li>Creating Virtual Networks (VPC) and different subnets in Azure is crucial for security because it allows you to isolate and segment your resources. This segmentation helps in implementing the principle of least privilege, limiting the exposure of resources to only necessary connections. Here's a link to the official Azure documentation on Virtual Networks that can provide you with more in-depth information and guidance: <a href="https://docs.microsoft.com/en-us/azure/virtual-network/" target="_blank">Azure Virtual Network documentation</a>.</li>
<li>When it comes to troubleshooting network configurations, a network architecture diagram removes the guesswork from the equation. It saves resources such as money and time when it comes to restarting a network. With an organized outline of how the components work together harmoniously, it is easier to pinpoint the specific areas where errors or problems occur. Please refer to here to learn about <a href="https://blog.rsisecurity.com/the-importance-of-having-a-network-diagram/" target="_blank">The importance of having a network diagram and How to create one.</a>.</li>
<li><a href="https://www.cisecurity.org/controls/continuous-vulnerability-assessment-and-remediation/" target="_blank">Continuous Vulnerability Assessment and Remediation</a></li>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Credential_Stuffing_Prevention_Cheat_Sheet.html" target="_blank">Credential Stuffing Prevention Cheat Sheet</a></li>
<li><a href="https://www.nist.gov/publications/digital-identity-guidelines" target="_blank">Digital Identity Guidelines</a></li>
<li><a href="https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/" target="_blank">How to Mitigate DDoS Attacks</a></li>
<li><a href="https://www.cisa.gov/news-events/news/understanding-denial-service-attacks" target="_blank">Understanding Denial-of-Service Attacks</a></li>
</ul>
<p>⭐️ ⭐️ ⭐️ ⭐️ ⭐️<br>Your feedback is so valuable and helps me improve my reviews. Please do not hesitate to share your feedback.</p>
<p>Good luck!</p>
</div> </div><!-- end ngIf: submission.general_comment --> <div critiques-editor="" critiques-accessor="critiquesAccessor" editable="false" is-career="currentProject.is_career" class="ng-isolate-scope"><!-- ngRepeat: section in critiquesAccessor.getSections() --><div ng-repeat="section in critiquesAccessor.getSections()" class="ng-scope"> <div section-critiques="" section="section" critiques="critiquesAccessor.getCritiques(section.id)" editable="editable" failed-required-placeholder="failedRequiredPlaceholder" passed-required-placeholder="passedRequiredPlaceholder" optional-placeholder="optionalPlaceholder" state="sectionCritiquesState[section.id]" is-career="isCareer" class="ng-isolate-scope"><div> <div class="row row-gap-small"></div> <h2 class="section-name ng-binding"> Section 1: Designing a Secure Network Architecture </h2> <div> <!-- ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon passed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Network design contains each of the following:</p>
<ul>
<li>An on-premise network that has 3 workstations in it. </li>
</ul>
<p>A Virtual Network with the following segments:</p>
<ul>
<li><p>Public DMZ with two web servers and load balancer in it. </p>
</li>
<li><p>Private DMZ with two database servers.</p>
</li>
<li><p>Management LAN with one management server in it. </p>
</li>
<li><p>Internal LAN with 5 workstations in it. </p>
</li>
<li><p>Private secure LAN with 3 database servers.</p>
</li>
</ul>
<p>Additionally include the following:</p>
<p>A VPN gateway connecting the on-premise network to your Virtual Network.</p>
<p>Show placement of security devices in the architecture, including load balancer(s), firewall(s), IDS/IPS device(s).</p>
<p>Show the flow of traffic, and remember to incorporate best security practices with the flow of traffic between the different subnets.</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>Network design contains all the required elements</p>
<ul>
<li>✅ An on-premise network that has 3 workstations in it.</li>
<li>✅ A Virtual Network with the following segments:<ul>
<li>✅ Public DMZ with two web servers and a load balancer in it.</li>
<li>✅ Private DMZ with two database servers.</li>
<li>✅ Management LAN with one management server in it.</li>
<li>✅ Internal LAN with 5 workstations in it.</li>
<li>✅ Private secure LAN with 3 database servers.</li>
</ul>
</li>
<li>✅ There is a VPN gateway connecting the on-premise network to your Virtual Network.</li>
<li>✅ The diagram shows the placement of security devices in the architecture, including load balancers, firewalls, and IDS/IPS devices.</li>
<li>✅ The diagram shows the traffic flow and incorporates best security practices with the flow of traffic between the different subnets.</li>
</ul>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604251/Screenshot_2024-04-20_at_13.10.31.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604251/Screenshot_2024-04-20_at_13.10.31.png" alt="Screenshot 2024-04-20 at 13.10.31.png"></a></p>
<hr>
<h5 id="-external-resource">📚 External Resource</h5>
<p>When it comes to troubleshooting network configurations, a network architecture diagram removes the guesswork from the equation. It saves resources such as money and time when it comes to restarting a network. With an organized outline of how the components work together harmoniously, it is easier to pinpoint the specific areas where errors or problems occur. Please refer to here to learn about <a href="https://blog.rsisecurity.com/the-importance-of-having-a-network-diagram/" target="_blank">The importance of having a network diagram and How to create one.</a>.</p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --> </div> </div> </div> </div><!-- end ngRepeat: section in critiquesAccessor.getSections() --><div ng-repeat="section in critiquesAccessor.getSections()" class="ng-scope"> <div section-critiques="" section="section" critiques="critiquesAccessor.getCritiques(section.id)" editable="editable" failed-required-placeholder="failedRequiredPlaceholder" passed-required-placeholder="passedRequiredPlaceholder" optional-placeholder="optionalPlaceholder" state="sectionCritiquesState[section.id]" is-career="isCareer" class="ng-isolate-scope"><div> <div class="row row-gap-small"></div> <h2 class="section-name ng-binding"> SECTION 2: BUILDING A SECURE NETWORK ARCHITECTURE </h2> <div> <!-- ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon passed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Screenshots show the following components of the secure network architecture created:</p>
<p>1) Two Azure Virtual Networks, one labeled for the DMZ and the other for the Internal</p>
<p>2) 2 subnets within the DMZ and 3 subnets within the Internal</p>
<p>3) DMZ subnets are labeled Public and Private</p>
<p>4) Internal LAN subnets are Management, Secure, and Enterprise</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>✅ There are two Azure virtual networks named DMZ and Internal<br>✅ The DMZ virtual network has two subnets: Public and Private<br>✅ The Internal virtual network has three subnets: Enterprise, Management, and Secure.</p>
<hr>
<h5 id="-external-resource">📚 External Resource</h5>
<p>Creating Virtual Networks (VPC) and different subnets in Azure is crucial for security because it allows you to isolate and segment your resources. This segmentation helps in implementing the principle of least privilege, limiting the exposure of resources to only necessary connections.</p>
<p>Here's a link to the official Azure documentation on Virtual Networks that can provide you with more in-depth information and guidance: <a href="https://docs.microsoft.com/en-us/azure/virtual-network/" target="_blank">Azure Virtual Network documentation</a>.</p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Screenshots show the following five VMs created:</p>
<p>1) One VM in each of the public and private DMZ subnets</p>
<p>2) One VM in each of the three internal subnets</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ Thanks for providing a screenshot of all your VMs. However, to meet this rubric item, you should provide screenshots of each VM that show the VM detail information (IP address, Subnetwork, etc.) Note the screenshot below as a reference</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1705245501/Screenshot_2024-01-14_at_19.17.13.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1705245501/Screenshot_2024-01-14_at_19.17.13.png" alt="SAMPLE"></a></p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><ul>
<li>Screenshot that shows the routing setup between the different subnets</li>
</ul>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ Good effort here. However, as you know we have two web servers in the Public DMZ that must be accessible worldwide. As a result, you should allow inbound traffic to the Public DMZ on ports 80 and 443 from any source. </p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604450/Screenshot_2024-04-20_at_13.13.56.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604450/Screenshot_2024-04-20_at_13.13.56.png" alt="Screenshot 2024-04-20 at 13.13.56.png"></a></p>
<hr>
<h5 id="-external-resource">📚 External Resource</h5>
<p><a href="https://learn.microsoft.com/en-us/azure/security/fundamentals/network-best-practices" target="_blank">This article</a> discusses a collection of Azure best practices to enhance your network security. These best practices are derived from our experience with Azure networking and the experiences of customers like yourself.</p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon passed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>1) A VPN giving the student direct access to the LAN has been created</p>
<p>2) Screenshot showing connectivity to the VPN</p>
<p>3) Screenshot showing connectivity to VMs within LAN while connected to VPN</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>✅ Thanks for providing screenshots that confirm <strong>Virtual Network Gateway</strong> has been set up correctly. Also, a screenshot showing network connectivity to VMs within LAN while connected to VPN.</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.17.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.17.png" alt="Screenshot 2024-04-20 at 13.15.17.png"></a></p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.24.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.24.png" alt="Screenshot 2024-04-20 at 13.15.24.png"></a></p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.35.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604547/Screenshot_2024-04-20_at_13.15.35.png" alt="Screenshot 2024-04-20 at 13.15.35.png"></a></p>
<hr>
<h5 id="-external-resource">📚 External Resource</h5>
<p>Using a VPN to connect to your private VPC in Azure enhances security by creating an encrypted and secure connection over the internet. This helps protect data in transit and ensures that communications between your on-premises infrastructure and Azure VPC are secure. For detailed information and guidance, you can refer to the official Azure documentation on <a href="https://learn.microsoft.com/en-us/azure/vpn-gateway/" target="_blank">VPN Gateway documentation</a>.</p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --> </div> </div> </div> </div><!-- end ngRepeat: section in critiquesAccessor.getSections() --><div ng-repeat="section in critiquesAccessor.getSections()" class="ng-scope"> <div section-critiques="" section="section" critiques="critiquesAccessor.getCritiques(section.id)" editable="editable" failed-required-placeholder="failedRequiredPlaceholder" passed-required-placeholder="passedRequiredPlaceholder" optional-placeholder="optionalPlaceholder" state="sectionCritiquesState[section.id]" is-career="isCareer" class="ng-isolate-scope"><div> <div class="row row-gap-small"></div> <h2 class="section-name ng-binding"> SECTION 3: CONTINUOUS MONITORING WITH A SIEM </h2> <div> <!-- ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Screenshots show the following have been created:</p>
<p>1) A VM in the private DMZ with the ELK Server built on it.</p>
<p>2) Routing configuration showing the only traffic allowed inbound to the server is from both of the virtual networks and Kibana only being accessible from the Internal Network.</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>✅ The ELK Server is successfully built on a VM in the private DMZ. </p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604651/Screenshot_2024-04-20_at_13.16.24.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604651/Screenshot_2024-04-20_at_13.16.24.png" alt="Screenshot 2024-04-20 at 13.16.24.png"></a></p>
<hr>
<p>❌ According to this rubric item, you should allow inbound traffic to the server from <strong>both of the virtual networks and Kibana only being accessible from the Internal Network</strong>. But as you can see in the screenshot below, you provide inbound traffic only from your public IP address <code>70.172.53.10?</code>.</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604650/Screenshot_2024-04-20_at_13.16.51.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713604650/Screenshot_2024-04-20_at_13.16.51.png" alt="Screenshot 2024-04-20 at 13.16.51.png"></a></p>
<hr>
<h5 id="-external-resource">📚 External Resource</h5>
<p>Continuous monitoring with a Security Information and Event Management (SIEM) solution in Azure is essential for maintaining a proactive and effective security posture. SIEM helps you centralize and analyze security data from various sources, enabling early detection of potential security threats and providing valuable insights into the security status of your Azure environment. For detailed information and guidance, you can refer to the official Azure documentation on <a href="https://learn.microsoft.com/en-us/azure/defender-for-cloud/" target="_blank">Azure Security Center</a></p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Screenshots show the following:</p>
<p>1) Filebeat service running and showing "Filebeat status Active"</p>
<p>2) Filebeat config file showing routing of logs to Elasticsearch</p>
<p>3) Simulate web traffic to your web servers using <a href="https://www.babylontraffic.com" target="_blank">https://www.babylontraffic.com</a></p>
<p>4) Web server logs appearing in Kibana</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ Thanks for providing the <code>3.2.1</code> screenshot but it is irrelevant to what this rubric asking for. According to this rubric item, you should provide a screenshot that clearly displays the Filebeat service running by showing <strong>Filebeat status Active</strong>. Please see the screenshot below as a reference</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1681726475/Screenshot_2023-04-17_at_14.13.30.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1681726475/Screenshot_2023-04-17_at_14.13.30.png" alt="SAMPLE"></a></p>
<hr>
<p>❌ Thanks for providing the <code>3.2.2</code> screenshot but it is irrelevant to what this rubric asking for. According to this rubric item, you should provide a screenshot of the Filebeat config file showing the routing of logs to Elasticsearch. See the screenshot below as a reference </p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1712337798/Screenshot_2024-04-05_at_21.09.35.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1712337798/Screenshot_2024-04-05_at_21.09.35.png" alt="SAMPLE"></a></p>
<hr>
<p>✅ Simulate web traffic to your web servers</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713605197/Screenshot_2024-04-20_at_13.25.57.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713605197/Screenshot_2024-04-20_at_13.25.57.png" alt="Screenshot 2024-04-20 at 13.25.57.png"></a></p>
<hr>
<p>✅ Web server logs appearing in Kibana</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713605199/Screenshot_2024-04-20_at_13.26.29.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713605199/Screenshot_2024-04-20_at_13.26.29.png" alt="Screenshot 2024-04-20 at 13.26.29.png"></a></p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Screenshots show these alerts have been created:</p>
<ul>
<li>Alert for a DoS attack.</li>
<li>Alert for a Brute Force attack</li>
<li>Alert for a scanning and reconnaissance attempt.</li>
</ul>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ Please provide screenshots of Denial of Service (DoS), Brute Force, and Port Scanning attack alert definitions in your report. See the screenshots below as references </p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715953/Screenshot_2024-03-29_at_16.36.08.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715953/Screenshot_2024-03-29_at_16.36.08.png" alt="Screenshot 2024-03-29 at 16.36.08.png"></a></p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715952/Screenshot_2024-03-29_at_16.35.25.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715952/Screenshot_2024-03-29_at_16.35.25.png" alt="Screenshot 2024-03-29 at 16.35.25.png"></a></p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715952/Screenshot_2024-03-29_at_16.34.35.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1711715952/Screenshot_2024-03-29_at_16.34.35.png" alt="Screenshot 2024-03-29 at 16.34.35.png"></a></p>
<hr>
<p>Please note the alarm definitions below as references:</p>
<h5 id="1-alert-rule-definition-for-a-dos-attack">1. Alert rule definition for a DoS attack</h5>
<pre><code><span class="hljs-type">WHEN</span>
  sum(bytes) <span class="hljs-type">OVER</span> all documents <span class="hljs-keyword">is</span> greater than <span class="hljs-number">2</span> times the <span class="hljs-number">7</span>-day rolling average
  <span class="hljs-type">AND</span> <span class="hljs-built_in">count</span>() <span class="hljs-type">OVER</span> source.ip <span class="hljs-keyword">is</span> above <span class="hljs-number">50</span> requests/<span class="hljs-built_in">min</span>
  <span class="hljs-type">AND</span> count_distinct(destination.ip) <span class="hljs-type">OVER</span> all documents <span class="hljs-keyword">is</span> less than <span class="hljs-number">10</span>
  <span class="hljs-type">AND</span> timeframe <span class="hljs-keyword">is</span> last <span class="hljs-number">5</span> minutes
</code></pre><p><strong>Explanation of adjustments:</strong></p>
<ul>
<li><strong><code>sum(bytes) OVER all documents is greater than 2 times the 7-day rolling average</code></strong>: Instead of an absolute value, comparing the current data to a historical baseline (e.g., a rolling average) can help identify abnormal spikes in traffic. Adjust the multiplier based on your specific environment.</li>
<li><strong><code>count() OVER source.ip is above 50 requests/min</code></strong>: Set a threshold for the number of requests per minute from a single source IP address. Adjust this value based on the typical traffic patterns in your network.</li>
<li><strong><code>count_distinct(destination.ip) OVER all documents is less than 10</code></strong>: Limit the number of distinct destination IP addresses to identify the potential concentration of traffic, which may be indicative of a DoS attack targeting specific resources.</li>
</ul>
<h5 id="2-alert-rule-definition-for-a-brute-force-attack">2. Alert rule definition for a Brute Force attack</h5>
<pre><code><span class="hljs-type">WHEN</span>
  <span class="hljs-built_in">count</span>() <span class="hljs-type">OVER</span> all documents <span class="hljs-keyword">is</span> greater than <span class="hljs-number">10</span>
  <span class="hljs-type">AND</span> <span class="hljs-built_in">count</span>() <span class="hljs-type">OVER</span> destination.ip, user.name <span class="hljs-keyword">is</span> greater than <span class="hljs-number">5</span> within <span class="hljs-number">1</span> minute
  <span class="hljs-type">AND</span> count_distinct(source.ip) <span class="hljs-type">OVER</span> destination.ip, user.name <span class="hljs-keyword">is</span> low within <span class="hljs-number">1</span> minute
  <span class="hljs-type">AND</span> timeframe <span class="hljs-keyword">is</span> last <span class="hljs-number">5</span> minutes
</code></pre><p><strong>Explanation of adjustments:</strong></p>
<ul>
<li><strong><code>count() OVER all documents is greater than 10</code></strong>: This condition checks for a threshold number of events within a specified timeframe, indicating potential suspicious activity.</li>
<li><strong><code>count() OVER destination.ip, user.name is greater than 5 within 1 minute</code></strong>: Focuses on the count of failed login attempts per destination IP and user name. If there are more than 5 failed login attempts within 1 minute, it may suggest a Brute Force attack.</li>
<li><strong><code>count_distinct(source.ip) OVER destination.ip, user.name is low within 1 minute</code></strong>: Checks for a low number of distinct source IP addresses attempting to log in for a specific destination IP and user name within 1 minute. A low number of distinct sources attempting many logins could be indicative of a Brute Force attack.</li>
<li><strong><code>timeframe is last 5 minutes</code></strong>: The rule focuses on recent data to detect short-term anomalies indicative of a potential Brute Force attack.</li>
</ul>
<h5 id="3-alert-rule-definition-for-a-port-scanning-attack">3. Alert rule definition for a port scanning attack</h5>
<pre><code><span class="hljs-type">WHEN</span>
  <span class="hljs-built_in">count</span>() <span class="hljs-type">OVER</span> all documents <span class="hljs-keyword">is</span> greater than <span class="hljs-number">10</span>
  <span class="hljs-type">AND</span> count_distinct(destination.port) <span class="hljs-type">OVER</span> source.ip <span class="hljs-keyword">is</span> greater than <span class="hljs-number">5</span> within <span class="hljs-number">1</span> minute
  <span class="hljs-type">AND</span> <span class="hljs-built_in">count</span>() <span class="hljs-type">OVER</span> source.ip, destination.port <span class="hljs-keyword">is</span> greater than <span class="hljs-number">5</span> within <span class="hljs-number">1</span> minute
  <span class="hljs-type">AND</span> timeframe <span class="hljs-keyword">is</span> last <span class="hljs-number">5</span> minutes
</code></pre><p><strong>Explanation of adjustments:</strong></p>
<ul>
<li><strong><code>count() OVER all documents is greater than 10</code></strong>: This condition checks for a threshold number of events within a specified timeframe, indicating potential suspicious activity.</li>
<li><strong><code>count_distinct(destination.port) OVER source.ip is greater than 5 within 1 minute</code></strong>: Focuses on the count of distinct destination ports for a specific source IP. If there are more than 5 distinct destination ports within 1 minute, it may suggest a port scanning attempt.</li>
<li><strong><code>count() OVER source.ip, destination.port is greater than 5 within 1 minute</code></strong>: Checks for a high number of connection attempts from a single source IP to multiple destination ports within 1 minute, which is indicative of port scanning behavior.</li>
<li><strong><code>timeframe is last 5 minutes</code></strong>: The rule focuses on recent data to detect short-term anomalies indicative of a potential port scanning attack.</li>
</ul>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Playbook details what the steps would be in response to each alert that was created. The remediation for each of the alerts should be included as well.</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ This item will be reviewed when you provide screenshots of DoS, Brute Force, and port scanning attacks' rules. </p>
<hr>
<p>Below are general recommendations for responding to DoS attacks, Brute Force attacks, and Port Scanning attacks</p>
<h5 id="1-denial-of-service-dos-attack-response-">1. Denial of Service (DoS) Attack Response:</h5>
<p><strong>Immediate Response:</strong></p>
<ul>
<li>Identify and isolate affected systems to minimize impact.</li>
<li>Implement rate limiting and traffic filtering to mitigate the attack.</li>
<li>Engage with your ISP or hosting provider to filter malicious traffic upstream.</li>
</ul>
<p><strong>Investigation and Analysis:</strong></p>
<ul>
<li>Analyze network traffic patterns to identify the source and nature of the attack.</li>
<li>Use flow data, logs, and intrusion detection/prevention system (IDS/IPS) alerts for analysis.</li>
</ul>
<p><strong> 📚 External Resource Websites:</strong></p>
<ul>
<li>Cloudflare: <a href="https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/" target="_blank">How to Mitigate DDoS Attacks</a></li>
<li>US-CERT: <a href="https://www.cisa.gov/news-events/news/understanding-denial-service-attacks" target="_blank">Understanding Denial-of-Service Attacks</a></li>
</ul>
<h5 id="2-brute-force-attack-response-">2. Brute Force Attack Response:</h5>
<p><strong>Immediate Response:</strong></p>
<ul>
<li>Lockout or temporarily block accounts with multiple failed login attempts.</li>
<li>Implement CAPTCHA or multi-factor authentication to enhance security.</li>
</ul>
<p><strong>Investigation and Analysis:</strong></p>
<ul>
<li>Analyze logs for patterns and identify affected accounts.</li>
<li>Correlate login attempts with source IP addresses.</li>
<li>Check for compromised accounts and reset passwords.</li>
</ul>
<p><strong> 📚 External Resource Websites:</strong></p>
<ul>
<li>OWASP: <a href="https://cheatsheetseries.owasp.org/cheatsheets/Credential_Stuffing_Prevention_Cheat_Sheet.html" target="_blank">Credential Stuffing Prevention Cheat Sheet</a></li>
<li>National Institute of Standards and Technology (NIST) <a href="https://www.nist.gov/publications/digital-identity-guidelines" target="_blank">Digital Identity Guidelines</a></li>
</ul>
<h5 id="3-port-scanning-attack-response-">3. Port Scanning Attack Response:</h5>
<p><strong> Immediate Response:</strong></p>
<ul>
<li>Implement network and host-based firewalls to block or limit scanning activity. </li>
<li>Monitor for and block suspicious IP addresses involved in the scanning.</li>
</ul>
<p><strong>Investigation and Analysis:</strong></p>
<ul>
<li>Analyze logs for patterns of port scanning behavior.</li>
<li>Look for a correlation between port scanning and other malicious activities.</li>
<li>Check for vulnerabilities on scanned ports and apply necessary patches.</li>
</ul>
<p><strong> 📚 External Resource Websites:</strong></p>
<ul>
<li>CIS Controls: <a href="https://www.cisecurity.org/controls/continuous-vulnerability-assessment-and-remediation/" target="_blank">Continuous Vulnerability Assessment and Remediation</a></li>
</ul>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --> </div> </div> </div> </div><!-- end ngRepeat: section in critiquesAccessor.getSections() --><div ng-repeat="section in critiquesAccessor.getSections()" class="ng-scope"> <div section-critiques="" section="section" critiques="critiquesAccessor.getCritiques(section.id)" editable="editable" failed-required-placeholder="failedRequiredPlaceholder" passed-required-placeholder="passedRequiredPlaceholder" optional-placeholder="optionalPlaceholder" state="sectionCritiquesState[section.id]" is-career="isCareer" class="ng-isolate-scope"><div> <div class="row row-gap-small"></div> <h2 class="section-name ng-binding"> Section 4: Zero Trust </h2> <div> <!-- ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon passed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>Zero Trust Model should incorporate the following:</p>
<ul>
<li>Identity</li>
<li>Devices</li>
<li>Apps</li>
<li>Network</li>
<li>Data</li>
<li>Infrastructure</li>
<li>Trusted and Untrusted Devices</li>
<li>Controls</li>
</ul>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>✅ You did great work by designing a segmented network with different zones and how they would verify trust.</p>
<p><a href="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713607078/Screenshot_2024-04-20_at_13.57.48.png" target="_blank"><img src="https://udacity-reviews-uploads.s3.us-west-2.amazonaws.com/_attachments/174586/1713607078/Screenshot_2024-04-20_at_13.57.48.png" alt="Screenshot 2024-04-20 at 13.57.48.png"></a></p>
</div> </div> </div> </div><!-- end ngIf: !!critique.observation --> <!-- ngIf: editable && !critiqueLocked() --> </div><!-- end ngIf: !isEditingCritique(critique.id) --> </div> </div><!-- end ngRepeat: critique in critiques --><div ng-repeat="critique in critiques" class="ng-scope"> <div row="" row-gap-small="" col-xs-12="" bg-white="" scroll-if="isCurrentEditingCritique(critique.id)" class="ng-isolate-scope"> <!-- ngIf: isEditingCritique(critique.id) --> <!-- ngIf: !isEditingCritique(critique.id) --><div class="critique-container ng-scope ng-isolate-scope" critique-view="" critique="critique" editable="editable" is-career="isCareer" edit-clicked="setEditingCritique(critique.id, true)" ng-if="!isEditingCritique(critique.id)"><div class="critique-view-header"> <div class="row result-label"> <div class="col-sm-1"> <div class="result-spacing"> <span ng-hide="isCareer" class="result-icon failed text-center"></span> </div> </div> <div class="col-xs-12 col-sm-10 critique-description ng-isolate-scope" marked="rubricItem.passed_description"><p>A detailed comparative analysis that accurately describes the differences between a Zero Trust model and modern network architecture design</p>
</div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: editable && critiqueLocked() --> </div> <!-- ngIf: !!critique.observation --><div ng-if="!!critique.observation" class="critique-view-body ng-scope"> <div class="row"> <div class="col-xs-12 col-sm-10 col-sm-offset-1"> <div class="p-slim ng-isolate-scope" marked="critique.observation"><p>❌ Good effort here. However, we're looking for a detailed report on how Zero Trust works and what the differences are between Zero Trust and the current modern security architecture. You should cover at least four of the following in this section:</p>
<ul>
<li>Difference in segmentation</li>
<li>User identification and access</li>
<li>Data security</li>
<li>The concept of trust</li>
<li>Why traditional perimeter defense is outdated due to the emergence of the cloud</li>
<li>Evolution of threat landscape.</li>
</ul>
