1. Why did the “standard-cluster-1” cluster fail to be created? How can I prevent this from happening with a new cluster?

2. Why did the “moose” cluster fail to be created? How can I prevent this from happening with a new cluster?

3. My “zebra” cluster worked fine with 2 nodes, I need to add one but it won’t work, why?

4. kubectl commands from the bastion VM to the “hippo” cluster are timing out, this works fine from another VM in another project called “Lampy”. Why do the requests from bastion timeout? 

5. I want to manage my “mongoose” cluster from my “narwhal” cluster but the kubectl commands keep failing. Why do my kubectl commands keep timing out? It works fine from my “bastion” VM.

6. In the “hippo” cluster, can you explain what the error message for “promsd” means? What is the cause? How can I fix this?

7. Why isn’t my “working” deployment working? The pod says it’s running!

8. My “job” workload doesn’t seem to be working. Can you tell me what is wrong or what the next steps in debugging it would be?

9. I have enabled autoscaling in my lion cluster, but my “bigjob” deployment still has unschedulable pods, why isn’t autoscaling working?

10. The “fab-four” deployment should have 4 pods, why are only 2 running?

11. My “mounter” pod is stuck in pending, why?

12. There is a service called “webserver”, I have tested the pod internally and I am confident that the pod is serving traffic properly. Why doesn’t the Load Balancer seem to work?

13. There is a service called “nginx”, I have tested the pod internally and I am confident that the pod is serving traffic properly. Why doesn’t the Load Balancer seem to work?

14. I created an ingress for my nginx workload since the service load balancer is not working. Why isn’t my ingress working?

15. My “working” ingress is returning 502 errors. Why is this happening?  How can I debug this?

16. My “echoheader” workload has been exposed with an ingress, yet there is still no external IP, what am I doing wrong?

17. In my “narwhal” cluster, I can’t reach my internal database which is located in another subnet on my shared VPC. **Note: I am able to reach my internal DB from my bastion VM** (not sure what this was supposed to be, but will configure it to be a networkPolicy issue)

18. Autoscaling is enabled on the “mongoose” cluster. There are multiple nodes with under 50% resource usage, why won’t it scale down?