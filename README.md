# Securing the Perimeter

## Project Overview

The "Securing the Perimeter" initiative is a project designed to address network security challenges experienced by XYZ, a leading cryptocurrency exchange. Despite being a highly dependable platform, the organization's rapid growth has strained its security posture, leading to vulnerabilities within its Perimeter Network Security. This situation has culminated in a recent breach that resulted in significant loss of assets, necessitating a comprehensive security overhaul. 

To this end, SecureCorp, a renowned cybersecurity consulting firm, has revamped XYZ's network architecture and implemented robust security measures. The project is divided into four primary sections, each focused on achieving specific objectives to enhance XYZ's overall security. The four main sections are:

1. **Designing a Secure Network Architecture**
2. **Building a Secure Network Architecture**
3. **Continuous Monitoring With a SIEM (Security Information and Event Management)**
4. **Zero Trust Model Implementation**

To successfully complete this project, each section has requirements that must be met before moving forward in the Udacity's Enterprise Security Engineer program. It was not easy, but after four submissions, the project was finally completed. The feedback I received from each submission was invaluable and helped me to ensure that the project was a complete success. Here are the four submissions' reviews:

1. **[Review #1](https://github.com/krillavilla/Securing-the-Perimeter/blob/main/Review_1.md)**
2. **Review #2**
3. **Review #3**
4. **Review #4**

### Section 1: Designing a Secure Network Architecture

This section entails designing a secure network architecture tailored to XYZ's business requirements. Key components include an on-premise network, a Virtual Network with segmented DMZs and LANs, and the incorporation of security devices such as firewalls and IDS/IPS.

<table>
  <thead>
    <tr>
      <th>Success Criteria</th>
      <th>Specifications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Design a secure network architecture based on business requirements</td>
      <td>
        <ul>
          <li>An on-premise network that has 3 workstations in it.</li>
          <li>A Virtual Network with segments:
            <ul>
              <li>Public DMZ with two web servers and load balancer in it.</li>
              <li>Private DMZ with two database servers.</li>
              <li>Management LAN with one management server in it.</li>
              <li>Internal LAN with 5 workstations in it.</li>
              <li>Private secure LAN with 3 database servers.</li>
            </ul>
          </li>
          <li>A VPN gateway connecting the on-premise network to your Virtual Network.</li>
          <li>Placement of security devices in the architecture, including load balancer(s), firewall(s), IDS/IPS device(s).</li>
          <li>Flow of traffic, incorporating best security practices between different subnets.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### Section 2: Building a Secure Network Architecture

The focus here is on implementing the designed architecture in Microsoft Azure. It involves creating Virtual Networks, subnets, and VMs, setting up secure network routing, and establishing a VPN for internal LAN access.

<table>
  <thead>
    <tr>
      <th>Success Criteria</th>
      <th>Specifications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Build a secure enterprise network in Azure</td>
      <td>
        <ul>
          <li>Two Azure Virtual Networks, one labeled for the DMZ and the other for the Internal</li>
          <li>2 subnets within the DMZ and 3 subnets within the Internal</li>
          <li>DMZ subnets are labeled Public and Private</li>
          <li>Internal LAN subnets are Management, Secure, and Enterprise</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Create VMs in Azure</td>
      <td>
        <ul>
          <li>One VM in each of the public and private DMZ subnets</li>
          <li>One VM in each of the three internal subnets</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Set up secure network routing</td>
      <td>
        <ul>
          <li>Screenshot that shows the routing setup between the different subnets</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Set up a VPN to access Azure Internal LAN</td>
      <td>
        <ul>
          <li>A VPN giving the student direct access to the LAN has been created</li>
          <li>Screenshot showing connectivity to the VPN</li>
          <li>Screenshot showing connectivity to VMs within LAN while connected to VPN</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### Section 3: Continuous Monitoring With a SIEM

This section involves setting up an ELK (Elasticsearch, Logstash, Kibana) Server for continuous monitoring. Tasks include ingesting logs into the SIEM, building alerts for potential security threats, and creating an Incident Response Playbook for proactive incident handling.

<table>
  <thead>
    <tr>
      <th>Success Criteria</th>
      <th>Specifications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Set up an ELK Server</td>
      <td>
        <ul>
          <li>A VM in the private DMZ with the ELK Server built on it.</li>
          <li>Routing configuration showing the only traffic allowed inbound to the server is from both of the virtual networks and Kibana only being accessible from the Internal Network.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Ingest logs into the SIEM</td>
      <td>
        <ul>
          <li>Filebeat service running and showing "Filebeat status Active"</li>
          <li>Filebeat config file showing routing of logs to Elasticsearch</li>
          <li>Simulate web traffic to your web servers using [https://www.babylontraffic.com](https://www.babylontraffic.com)</li>
          <li>Web server logs appearing in Kibana</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Build alerts for the SIEM</td>
      <td>
        <ul>
          <li>Alert for a DoS attack.</li>
          <li>Alert for a Brute Force attack</li>
          <li>Alert for a scanning and reconnaissance attempt.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Plan for future incidents by writing an Incident Response Playbook</td>
      <td>
        <ul>
          <li>Playbook details what the steps would be in response to each alert that was created. The remediation for each of the alerts should be included as well.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>


### Section 4: Zero Trust Model

The final section revolves around designing and implementing a Zero Trust Model. This includes considerations for identity, device, application, network, data, and infrastructure security. A comparison between Zero Trust and modern security architecture is also provided.

<table>
  <thead>
    <tr>
      <th>Success Criteria</th>
      <th>Specifications</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Design a Zero Trust Model</td>
      <td>
        <ul>
          <li>Zero Trust Model should incorporate the following:</li>
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
        </ul>
      </td>
    </tr>
    <tr>
      <td>Demonstrate knowledge of Zero Trust models by describing the differences between Zero Trust and modern security architecture</td>
      <td>
        <ul>
          <li>A detailed comparative analysis that accurately describes the differences between a Zero Trust model and modern network architecture design</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
