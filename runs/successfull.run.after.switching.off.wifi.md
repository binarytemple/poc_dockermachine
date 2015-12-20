```
[~%]docker-machine -D create default -d vmwarefusion
Docker Machine Version: 0.5.0 (HEAD)
Found binary path at /usr/local/bin/docker-machine-driver-vmwarefusion
Launching plugin server for driver vmwarefusion
Plugin server listening at address 127.0.0.1:49219
() Calling RpcServerDriver.GetVersion
Using API Version 1
() Calling RpcServerDriver.SetConfigRaw
() Calling RpcServerDriver.GetMachineName
(flag-lookup) Calling RpcServerDriver.GetCreateFlags
Making call to close connection to plugin binary
Making call to close driver server
(flag-lookup) Calling RpcServerDriver.Close
Successfully made call to close driver server
Found binary path at /usr/local/bin/docker-machine-driver-vmwarefusion
Launching plugin server for driver vmwarefusion
Plugin server listening at address 127.0.0.1:49223
() Calling RpcServerDriver.GetVersion
Using API Version 1
() Calling RpcServerDriver.SetConfigRaw
() Calling RpcServerDriver.GetMachineName
(default) Calling RpcServerDriver.GetMachineName
(default) Calling RpcServerDriver.DriverName
(default) Calling RpcServerDriver.GetCreateFlags
(default) Calling RpcServerDriver.SetConfigFromFlags
Running pre-create checks...
(default) Calling RpcServerDriver.PreCreateCheck
(default) Calling RpcServerDriver.GetConfigRaw
(default) Calling RpcServerDriver.GetConfigRaw
Creating machine...
(default) Calling RpcServerDriver.Create
(default) OUT | Creating SSH key...
(default) OUT | Creating VM...
(default) OUT | Starting default...
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun start /Users/bryanhunt/.docker/machine/machines/default/default.vmx nogui
(default) OUT | Waiting for VM to come online...
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: i/o timeout
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: i/o timeout
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: i/o timeout
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down


(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: connect: host is down
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | SSH Daemon not responding yet: dial tcp 192.168.191.132:22: i/o timeout
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) DBG | Got an ip: 192.168.191.132
(default) DBG | Creating Tar key bundle...
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser directoryExistsInGuest /Users/bryanhunt/.docker/machine/machines/default/default.vmx /var/lib/boot2docker
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser CopyFileFromHostToGuest /Users/bryanhunt/.docker/machine/machines/default/default.vmx /Users/bryanhunt/.docker/machine/machines/default/userdata.tar /home/docker/userdata.tar
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser runScriptInGuest /Users/bryanhunt/.docker/machine/machines/default/default.vmx /bin/sh sudo /bin/mv /home/docker/userdata.tar /var/lib/boot2docker/userdata.tar && sudo tar xf /var/lib/boot2docker/userdata.tar -C /home/docker/ > /var/log/userdata.log 2>&1 && sudo chown -R docker:staff /home/docker
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser enableSharedFolders /Users/bryanhunt/.docker/machine/machines/default/default.vmx
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser addSharedFolder /Users/bryanhunt/.docker/machine/machines/default/default.vmx Users /Users
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun -gu docker -gp tcuser runScriptInGuest /Users/bryanhunt/.docker/machine/machines/default/default.vmx /bin/sh [ ! -d /Users ]&& sudo mkdir /Users; [ -f /usr/local/bin/vmhgfs-fuse ]&& sudo /usr/local/bin/vmhgfs-fuse -o allow_other .host:/Users /Users || sudo mount -t vmhgfs .host:/Users /Users
(default) Calling RpcServerDriver.GetConfigRaw
(default) Calling RpcServerDriver.GetConfigRaw
(default) Calling RpcServerDriver.DriverName
Waiting for machine to be running, this may take a few minutes...
(default) Calling RpcServerDriver.GetState
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
Machine is running, waiting for SSH to be available...
Getting to WaitForSSH function...
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
exit 0
SSH cmd err, output: <nil>:
Detecting operating system of created instance...
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
cat /etc/os-release
SSH cmd err, output: <nil>: NAME=Boot2Docker
VERSION=1.9.1
ID=boot2docker
ID_LIKE=tcl
VERSION_ID=1.9.1
PRETTY_NAME="Boot2Docker 1.9.1 (TCL 6.4.1); master : cef800b - Fri Nov 20 19:33:59 UTC 2015"
ANSI_COLOR="1;34"
HOME_URL="http://boot2docker.io"
SUPPORT_URL="https://github.com/boot2docker/boot2docker"
BUG_REPORT_URL="https://github.com/boot2docker/boot2docker/issues"

found compatible host: boot2docker
Provisioning created instance...
(default) Calling RpcServerDriver.GetMachineName
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
sudo /usr/bin/sethostname default && echo "default" | sudo tee /var/lib/boot2docker/etc/hostname
SSH cmd err, output: <nil>: Setting hostname to default Done.
default

(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
netstat -a
SSH cmd err, output: <nil>: Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State
tcp        0      0 0.0.0.0:ssh             0.0.0.0:*               LISTEN
tcp       28      0 192.168.191.132:ssh     192.168.191.1:49251     ESTABLISHED
tcp        0      0 :::ssh                  :::*                    LISTEN
tcp        0      0 :::2376                 :::*                    LISTEN
Active UNIX domain sockets (servers and established)
Proto RefCnt Flags       Type       State         I-Node Path
unix  2      [ ACC ]     STREAM     LISTENING      18374 /var/lib/docker/network/files/72bc6cbf7dbd50040b6e6e2e26fe7e3ac8f82e9712a34d9d3ea7581108927302.sock
unix  2      [ ACC ]     STREAM     LISTENING      18292 /var/run/docker.sock
unix  2      [ ACC ]     STREAM     LISTENING      18106 /var/run/acpid.socket
unix  2      [ ACC ]     SEQPACKET  LISTENING      14281 /run/udev/control
unix  3      [ ]         STREAM     CONNECTED      18853
unix  3      [ ]         STREAM     CONNECTED      18852
unix  3      [ ]         DGRAM                     14290
unix  3      [ ]         DGRAM                     14291

(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
sudo mkdir -p /var/lib/boot2docker
SSH cmd err, output: <nil>:
(default) Calling RpcServerDriver.GetMachineName
(default) Calling RpcServerDriver.GetIP
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
Copying certs to the local machine directory...
generating server cert: /Users/bryanhunt/.docker/machine/machines/default/server.pem ca-key=/Users/bryanhunt/.docker/machine/certs/ca.pem private-key=/Users/bryanhunt/.docker/machine/certs/ca-key.pem org=bryanhunt.default
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
sudo /etc/init.d/docker stop
SSH cmd err, output: <nil>:
Copying certs to the remote machine...
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
printf '%s' '-----BEGIN CERTIFICATE-----
MIIC1jCCAb6gAwIBAgIRAO3UC97awsTch4n7DmJNAmMwDQYJKoZIhvcNAQELBQAw
FDESMBAGA1UEChMJYnJ5YW5odW50MB4XDTE1MTIxMDA5NDgwMFoXDTE4MTEyNDA5
NDgwMFowFDESMBAGA1UEChMJYnJ5YW5odW50MIIBIjANBgkqhkiG9w0BAQEFAAOC
AQ8AMIIBCgKCAQEA7Roi8Mv1wd8i6sC7vdO44C4RmjZ64TfaPBrrs/FJQYLXVU7Y
ORSPyR4fzakVW1D9tudoFvoqi+VF1XT78VBnzsOX+E19WOWd9AOIANbpLa5sXlAE
LnbtMacSdoD02ElTEPi2qiVoFGOChqG1q3DWczJWPH6uVtv85CFLOOtlHrw8ZOjw
eoYAimXVF7gTjbqYc+ZD7itg/3/Ll6kBHGCb1FrZWjNqjSGngjOu1dWKc+TsHayq
g1bbh4sQW8xa9LdC0NaKLBDuLHtEyXYWs0mPb5QY03XWkNDdWJY2tIHzHovH5tap
u6uHjgKM32Y7y53hmdC26FvzGLamjtI2sW3e6wIDAQABoyMwITAOBgNVHQ8BAf8E
BAMCAqwwDwYDVR0TAQH/BAUwAwEB/zANBgkqhkiG9w0BAQsFAAOCAQEATAp5K6zk
2lgvffG8q5uPrA8grBgcCyMTl4k/S8ahOLGRvIoEF7FKFaiRg4DM2KCaQUR1hjIO
v0KeHn4j27LVf+zDu5Es9IPRKI64OZA/gqtb99FPh49VKW9g73Xxoz+LcfSZSl/1
Kms/fWrh7yMkiHooa9pYqgQRInYSB+aXHDqjVYBHsXi2ggc3DdR9md8yDqrJhi3a
HM6i/wInfn+PeLA8prv0i4MTiGvgZqYU1M/DSyL3YnycyUZ01mgFj7cq+PquIO+1
2AXpgCS4OneAofepXyk5/J0wlxbQ1d58DQIed5RgH6QBCw7P+McDK1pfYdZVEooM
n88keM6RWF1vDA==
-----END CERTIFICATE-----
' | sudo tee /var/lib/boot2docker/ca.pem
SSH cmd err, output: <nil>: -----BEGIN CERTIFICATE-----
MIIC1jCCAb6gAwIBAgIRAO3UC97awsTch4n7DmJNAmMwDQYJKoZIhvcNAQELBQAw
FDESMBAGA1UEChMJYnJ5YW5odW50MB4XDTE1MTIxMDA5NDgwMFoXDTE4MTEyNDA5
NDgwMFowFDESMBAGA1UEChMJYnJ5YW5odW50MIIBIjANBgkqhkiG9w0BAQEFAAOC
AQ8AMIIBCgKCAQEA7Roi8Mv1wd8i6sC7vdO44C4RmjZ64TfaPBrrs/FJQYLXVU7Y
ORSPyR4fzakVW1D9tudoFvoqi+VF1XT78VBnzsOX+E19WOWd9AOIANbpLa5sXlAE
LnbtMacSdoD02ElTEPi2qiVoFGOChqG1q3DWczJWPH6uVtv85CFLOOtlHrw8ZOjw
eoYAimXVF7gTjbqYc+ZD7itg/3/Ll6kBHGCb1FrZWjNqjSGngjOu1dWKc+TsHayq
g1bbh4sQW8xa9LdC0NaKLBDuLHtEyXYWs0mPb5QY03XWkNDdWJY2tIHzHovH5tap
u6uHjgKM32Y7y53hmdC26FvzGLamjtI2sW3e6wIDAQABoyMwITAOBgNVHQ8BAf8E
BAMCAqwwDwYDVR0TAQH/BAUwAwEB/zANBgkqhkiG9w0BAQsFAAOCAQEATAp5K6zk
2lgvffG8q5uPrA8grBgcCyMTl4k/S8ahOLGRvIoEF7FKFaiRg4DM2KCaQUR1hjIO
v0KeHn4j27LVf+zDu5Es9IPRKI64OZA/gqtb99FPh49VKW9g73Xxoz+LcfSZSl/1
Kms/fWrh7yMkiHooa9pYqgQRInYSB+aXHDqjVYBHsXi2ggc3DdR9md8yDqrJhi3a
HM6i/wInfn+PeLA8prv0i4MTiGvgZqYU1M/DSyL3YnycyUZ01mgFj7cq+PquIO+1
2AXpgCS4OneAofepXyk5/J0wlxbQ1d58DQIed5RgH6QBCw7P+McDK1pfYdZVEooM
n88keM6RWF1vDA==
-----END CERTIFICATE-----

(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
printf '%s' '-----BEGIN CERTIFICATE-----
MIIDFjCCAf6gAwIBAgIRAMZQjXREjYEs096emZE9TAEwDQYJKoZIhvcNAQELBQAw
FDESMBAGA1UEChMJYnJ5YW5odW50MB4XDTE1MTIyMDE2MzUwMFoXDTE4MTIwNDE2
MzUwMFowHDEaMBgGA1UEChMRYnJ5YW5odW50LmRlZmF1bHQwggEiMA0GCSqGSIb3
DQEBAQUAA4IBDwAwggEKAoIBAQDkudmsV7wf7eCPjrYv/MrB347FSgAf4RsYodLC
dqMnjTMFDgP+CqNKt8b33a4bbh1BKX71H53ggW7Rxc67R3HDyZ9TcNh0DOIYeMvz
GkT4C/fDYpQb2NOj2a/elFF1zA+iUE68oJbJVciGDdv4Q3ACoINqDrV245+ZMj2E
3mNAdsTxkke9Al4JsuUof0s0LWCX1b/eEGTtQeUJGbeo+7/nu2OL0Lt8rlC3OSgM
aTohJwhPCmpto3N1UvURnN97qgz862j+ViVCj+IsTnKHHD6/+sMz/vNt7ts7Tp3s
jN1A8d+DaKYwzqtr3CnF8VciUrlMoOqPMAw4o60vxF3QClf7AgMBAAGjWzBZMA4G
A1UdDwEB/wQEAwIDqDAdBgNVHSUEFjAUBggrBgEFBQcDAgYIKwYBBQUHAwEwDAYD
VR0TAQH/BAIwADAaBgNVHREEEzARgglsb2NhbGhvc3SHBMCov4QwDQYJKoZIhvcN
AQELBQADggEBADHXMToGo0lBYDTq1Bm4KAft8FWYUEQq9JEg1NwylEzhakqBW/fg
odpw5/dfrhk784wUq89HaFo9jHw8jceMW/mgejt2EoYlzG0SduPIBe4dALcdgMNu
mukP9phkFYQtnJVy/0CPAakSZXzjk3NY0SrCN77I32GoQNYwM5hp3iKsVIhrhe/l
mTxoJLCD8jDqedE2nGbN5d+K3LmCHAn0Xzn48UER1qcewh/XnjFRtX+TAkmJqBVP
UMKc9lKN/ILtk2K1GVT/rvxlHK4qD7o8bblXqqcImKCIi4k7o48zYPOOmv78sYUN
mGULMGk/P1A8gJoBumEcNa8iaUCje2HGedE=
-----END CERTIFICATE-----
' | sudo tee /var/lib/boot2docker/server.pem
SSH cmd err, output: <nil>: -----BEGIN CERTIFICATE-----
MIIDFjCCAf6gAwIBAgIRAMZQjXREjYEs096emZE9TAEwDQYJKoZIhvcNAQELBQAw
FDESMBAGA1UEChMJYnJ5YW5odW50MB4XDTE1MTIyMDE2MzUwMFoXDTE4MTIwNDE2
MzUwMFowHDEaMBgGA1UEChMRYnJ5YW5odW50LmRlZmF1bHQwggEiMA0GCSqGSIb3
DQEBAQUAA4IBDwAwggEKAoIBAQDkudmsV7wf7eCPjrYv/MrB347FSgAf4RsYodLC
dqMnjTMFDgP+CqNKt8b33a4bbh1BKX71H53ggW7Rxc67R3HDyZ9TcNh0DOIYeMvz
GkT4C/fDYpQb2NOj2a/elFF1zA+iUE68oJbJVciGDdv4Q3ACoINqDrV245+ZMj2E
3mNAdsTxkke9Al4JsuUof0s0LWCX1b/eEGTtQeUJGbeo+7/nu2OL0Lt8rlC3OSgM
aTohJwhPCmpto3N1UvURnN97qgz862j+ViVCj+IsTnKHHD6/+sMz/vNt7ts7Tp3s
jN1A8d+DaKYwzqtr3CnF8VciUrlMoOqPMAw4o60vxF3QClf7AgMBAAGjWzBZMA4G
A1UdDwEB/wQEAwIDqDAdBgNVHSUEFjAUBggrBgEFBQcDAgYIKwYBBQUHAwEwDAYD
VR0TAQH/BAIwADAaBgNVHREEEzARgglsb2NhbGhvc3SHBMCov4QwDQYJKoZIhvcN
AQELBQADggEBADHXMToGo0lBYDTq1Bm4KAft8FWYUEQq9JEg1NwylEzhakqBW/fg
odpw5/dfrhk784wUq89HaFo9jHw8jceMW/mgejt2EoYlzG0SduPIBe4dALcdgMNu
mukP9phkFYQtnJVy/0CPAakSZXzjk3NY0SrCN77I32GoQNYwM5hp3iKsVIhrhe/l
mTxoJLCD8jDqedE2nGbN5d+K3LmCHAn0Xzn48UER1qcewh/XnjFRtX+TAkmJqBVP
UMKc9lKN/ILtk2K1GVT/rvxlHK4qD7o8bblXqqcImKCIi4k7o48zYPOOmv78sYUN
mGULMGk/P1A8gJoBumEcNa8iaUCje2HGedE=
-----END CERTIFICATE-----

(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
printf '%s' '-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEA5LnZrFe8H+3gj462L/zKwd+OxUoAH+EbGKHSwnajJ40zBQ4D
/gqjSrfG992uG24dQSl+9R+d4IFu0cXOu0dxw8mfU3DYdAziGHjL8xpE+Av3w2KU
G9jTo9mv3pRRdcwPolBOvKCWyVXIhg3b+ENwAqCDag61duOfmTI9hN5jQHbE8ZJH
vQJeCbLlKH9LNC1gl9W/3hBk7UHlCRm3qPu/57tji9C7fK5QtzkoDGk6IScITwpq
baNzdVL1EZzfe6oM/Oto/lYlQo/iLE5yhxw+v/rDM/7zbe7bO06d7IzdQPHfg2im
MM6ra9wpxfFXIlK5TKDqjzAMOKOtL8Rd0ApX+wIDAQABAoIBAQDRaYNtMmqwhRe7
+DrAFuAAv1E1OrqAdZZcaBTSLNLWbIXQ0/M9zbmRuE84M0OsI5YvSfHONeNTYM34
y/WqLBBx5JC2UbQsFHuRUk/QxTVuMW7n+cKG+G9VLgLCc+NdSbbqskJUm2dS8PKG
IfxLAlt0XEfVe6ATOPavyXrfwsj2g8vd3rYCgdsYzuvO9Pgkk6B1TW+qjQ36uDgX
uZaIIPWqaL8mkcR8/S5nwBj41+ystSFXD/anU1lrSNLekB71nrxD/2EqXTR1KDpi
RIKvlY5qEJMgNQiDXgroD3Lisri8eXlDzELi4DMFe7M38PPr3b4JQM7277cNwDWT
9RKCe+sZAoGBAOcaZr4zVCIwkPc6AxxXQLgtMjj85e9Do8lRMIrxhBZsIf2HX0Sx
L7YCsta8H+D+lwKaxN+Xzc9r9hss9R5zwBo3lLlSjjv/nTX+HoGYNY/qBvw2Gt+j
fh+tZffDXOuI41JKy6tjJXEUZoVgK3WXk1twGFaVN2q8AbFibaknr8LHAoGBAP1d
46+51RX2qARkBcaXwfe0YocQJRyKpYYwH7C40VtICqhb/tZFSCiOdzylrP5GH9Ko
1hUbBPLDQnMd7828zeNqwlHRlIFkpmYdVuk/uUib34GvJPIWnqoCntBl7RqmhmxL
t1SmZ7D8CgbENLctR41ggQ0TmM5qNYZSAWvrtw0tAoGBALF4vN3jXQDEew7gJfNl
rfXB/4dz7r/HGchH6RdKUT1G3PNtOePujc0gVWZCIdkOqbj+UaHDWfGn3t8Pr00r
ZqK7fCK1GzVIHtqPw62RzdAu0B5vDkQfsYNyDZQvGvRlsuxHNBDxmpc0K2bRa45q
UGcvtgEHpf75UfN+uufj6j2RAoGAAZTJa/pT6xwr9kMNiiy+SCZ3CvK92IzA9bJt
MDQnElPDxUM1tu6dwasJ8XXzO28CmdT16RHPGRjA3GkOaxFHk6jB57LQI3KWW0LJ
nREJvftDDNMj/uLHQLZdeV15elYZtqlOTpfvQ7p+8YXd8lq0/JvikktSA8/D37+5
RIwnC00CgYEAsdCc0Llf4iWToEYEwGiuNSx/xgZv8VvZLPHGLZcpy60A/O8g7L5Y
dKailJfQYk+F+ammYhz8z/6Al8AadvpC28SZ8bf448IoVxQmjhcLIgxytB2CvGfJ
PzgrPXTQ9P5QNXUGuB8VNEB5MLqpJWwUW4DztS0tTM4Ot5MIs43acxs=
-----END RSA PRIVATE KEY-----
' | sudo tee /var/lib/boot2docker/server-key.pem
SSH cmd err, output: <nil>: -----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEA5LnZrFe8H+3gj462L/zKwd+OxUoAH+EbGKHSwnajJ40zBQ4D
/gqjSrfG992uG24dQSl+9R+d4IFu0cXOu0dxw8mfU3DYdAziGHjL8xpE+Av3w2KU
G9jTo9mv3pRRdcwPolBOvKCWyVXIhg3b+ENwAqCDag61duOfmTI9hN5jQHbE8ZJH
vQJeCbLlKH9LNC1gl9W/3hBk7UHlCRm3qPu/57tji9C7fK5QtzkoDGk6IScITwpq
baNzdVL1EZzfe6oM/Oto/lYlQo/iLE5yhxw+v/rDM/7zbe7bO06d7IzdQPHfg2im
MM6ra9wpxfFXIlK5TKDqjzAMOKOtL8Rd0ApX+wIDAQABAoIBAQDRaYNtMmqwhRe7
+DrAFuAAv1E1OrqAdZZcaBTSLNLWbIXQ0/M9zbmRuE84M0OsI5YvSfHONeNTYM34
y/WqLBBx5JC2UbQsFHuRUk/QxTVuMW7n+cKG+G9VLgLCc+NdSbbqskJUm2dS8PKG
IfxLAlt0XEfVe6ATOPavyXrfwsj2g8vd3rYCgdsYzuvO9Pgkk6B1TW+qjQ36uDgX
uZaIIPWqaL8mkcR8/S5nwBj41+ystSFXD/anU1lrSNLekB71nrxD/2EqXTR1KDpi
RIKvlY5qEJMgNQiDXgroD3Lisri8eXlDzELi4DMFe7M38PPr3b4JQM7277cNwDWT
9RKCe+sZAoGBAOcaZr4zVCIwkPc6AxxXQLgtMjj85e9Do8lRMIrxhBZsIf2HX0Sx
L7YCsta8H+D+lwKaxN+Xzc9r9hss9R5zwBo3lLlSjjv/nTX+HoGYNY/qBvw2Gt+j
fh+tZffDXOuI41JKy6tjJXEUZoVgK3WXk1twGFaVN2q8AbFibaknr8LHAoGBAP1d
46+51RX2qARkBcaXwfe0YocQJRyKpYYwH7C40VtICqhb/tZFSCiOdzylrP5GH9Ko
1hUbBPLDQnMd7828zeNqwlHRlIFkpmYdVuk/uUib34GvJPIWnqoCntBl7RqmhmxL
t1SmZ7D8CgbENLctR41ggQ0TmM5qNYZSAWvrtw0tAoGBALF4vN3jXQDEew7gJfNl
rfXB/4dz7r/HGchH6RdKUT1G3PNtOePujc0gVWZCIdkOqbj+UaHDWfGn3t8Pr00r
ZqK7fCK1GzVIHtqPw62RzdAu0B5vDkQfsYNyDZQvGvRlsuxHNBDxmpc0K2bRa45q
UGcvtgEHpf75UfN+uufj6j2RAoGAAZTJa/pT6xwr9kMNiiy+SCZ3CvK92IzA9bJt
MDQnElPDxUM1tu6dwasJ8XXzO28CmdT16RHPGRjA3GkOaxFHk6jB57LQI3KWW0LJ
nREJvftDDNMj/uLHQLZdeV15elYZtqlOTpfvQ7p+8YXd8lq0/JvikktSA8/D37+5
RIwnC00CgYEAsdCc0Llf4iWToEYEwGiuNSx/xgZv8VvZLPHGLZcpy60A/O8g7L5Y
dKailJfQYk+F+ammYhz8z/6Al8AadvpC28SZ8bf448IoVxQmjhcLIgxytB2CvGfJ
PzgrPXTQ9P5QNXUGuB8VNEB5MLqpJWwUW4DztS0tTM4Ot5MIs43acxs=
-----END RSA PRIVATE KEY-----

(default) Calling RpcServerDriver.GetURL
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.DriverName
Setting Docker configuration on the remote daemon...
(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
printf %s "
EXTRA_ARGS='
--label provider=vmwarefusion

'
CACERT=/var/lib/boot2docker/ca.pem
DOCKER_HOST='-H tcp://0.0.0.0:2376'
DOCKER_STORAGE=aufs
DOCKER_TLS=auto
SERVERKEY=/var/lib/boot2docker/server-key.pem
SERVERCERT=/var/lib/boot2docker/server.pem


" | sudo tee /var/lib/boot2docker/profile
SSH cmd err, output: <nil>:
EXTRA_ARGS='
--label provider=vmwarefusion

'
CACERT=/var/lib/boot2docker/ca.pem
DOCKER_HOST='-H tcp://0.0.0.0:2376'
DOCKER_STORAGE=aufs
DOCKER_TLS=auto
SERVERKEY=/var/lib/boot2docker/server-key.pem
SERVERCERT=/var/lib/boot2docker/server.pem



(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
sudo /etc/init.d/docker start
SSH cmd err, output: <nil>: Device "eth1" does not exist.
Need TLS certs for default,127.0.0.1,192.168.191.132
-------------------
Generate server cert
/usr/local/bin/generate_cert --host=default,127.0.0.1,192.168.191.132 --ca=/var/lib/boot2docker/ca.pem --ca-key=/var/lib/boot2docker/tls/cakey.pem --cert=/var/lib/boot2docker/server.pem --key=/var/lib/boot2docker/server-key.pem --org=Boot2Docker
2015/12/20 16:40:47 Preventing overwrite: the following files already exist: "/var/lib/boot2docker/server.pem" "/var/lib/boot2docker/server-key.pem". To overwrite files, add `--overwrite`.

(default) Calling RpcServerDriver.GetSSHHostname
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
(default) Calling RpcServerDriver.GetSSHPort
(default) Calling RpcServerDriver.GetSSHKeyPath
(default) Calling RpcServerDriver.GetSSHUsername
Using SSH client type: external
About to run SSH command:
netstat -a
SSH cmd err, output: <nil>: Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State
tcp        0      0 0.0.0.0:ssh             0.0.0.0:*               LISTEN
tcp       28      0 192.168.191.132:ssh     192.168.191.1:49263     ESTABLISHED
tcp        0      0 :::ssh                  :::*                    LISTEN
tcp        0      0 :::2376                 :::*                    LISTEN
Active UNIX domain sockets (servers and established)
Proto RefCnt Flags       Type       State         I-Node Path
unix  2      [ ACC ]     STREAM     LISTENING      19398 /var/lib/docker/network/files/fa6bd24f49680a377264005b399693d0f13cf9a2bfd033d9bfc89690bb3012cf.sock
unix  2      [ ACC ]     STREAM     LISTENING      19308 /var/run/docker.sock
unix  2      [ ACC ]     STREAM     LISTENING      18106 /var/run/acpid.socket
unix  2      [ ACC ]     SEQPACKET  LISTENING      14281 /run/udev/control
unix  3      [ ]         STREAM     CONNECTED      19488
unix  3      [ ]         STREAM     CONNECTED      19487
unix  3      [ ]         DGRAM                     14290
unix  3      [ ]         DGRAM                     14291

(default) Calling RpcServerDriver.GetIP
(default) DBG | executing: /Applications/VMware Fusion.app/Contents/Library/vmrun list
(default) DBG | MAC address in VMX: 00:0c:29:a3:b9:04
(default) DBG | IP found in DHCP lease table: 192.168.191.132
Reticulating splines...
(default) Calling RpcServerDriver.GetConfigRaw
(default) Calling RpcServerDriver.GetConfigRaw
To see how to connect Docker to this machine, run: docker-machine env default
[~%]
```

```
eval "$(docker-machine env default)"
docker-machine ssh default
```

```
docker@default:~$ docker run swarm create
Unable to find image 'swarm:latest' locally
latest: Pulling from library/swarm
d681c900c6e3: Pull complete
188de6f24f3f: Pull complete
90b2ffb8d338: Pull complete
237af4efea94: Pull complete
3b3fc6f62107: Pull complete
7e6c9135b308: Pull complete
986340ab62f0: Pull complete
a9975e2cc0a3: Pull complete
Digest: sha256:c21fd414b0488637b1f05f13a59b032a3f9da5d818d31da1a4ca98a84c0c781b
Status: Downloaded newer image for swarm:latest
3e6186eb75760eaf4233357ffbcc1edf
```



```
[/common/poc_dockermachine/runs%]docker-machine create \
    -d vmwarefusion  \
    --swarm \
    --swarm-discovery token://3e6186eb75760eaf4233357ffbcc1edf  \
    swarm-agent-00
Running pre-create checks...
Creating machine...
Waiting for machine to be running, this may take a few minutes...
Machine is running, waiting for SSH to be available...
Detecting operating system of created instance...
Provisioning created instance...
Copying certs to the local machine directory...
Copying certs to the remote machine...
Setting Docker configuration on the remote daemon...
Configuring swarm...
To see how to connect Docker to this machine, run: docker-machine env swarm-agent-00
```
