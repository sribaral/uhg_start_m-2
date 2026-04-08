.
├── .github/
│   ├── audit-logs/
│   │   ├── 2026-03-20-13.txt
│   │   ├── 2026-03-20-14.txt
│   │   ├── 2026-03-20-16.txt
│   │   ├── 2026-03-20-3.txt
│   │   ├── 2026-03-20-4.txt
│   │   ├── 2026-03-20-5.txt
│   │   ├── 2026-03-20-7.txt
│   │   ├── 2026-03-20-8.txt
│   │   ├── 2026-03-23-17.txt
│   │   ├── 2026-03-23-18.txt
│   │   ├── 2026-03-24-20.txt
│   │   ├── 2026-03-26-21.txt
│   │   └── 2026-03-26-22.txt
│   ├── docs/
│   │   ├── gcp-cloudguru-scan.md
│   │   ├── gcp-tf-add-labels.md
│   │   ├── gcp-tf-drift-scan.md
│   │   ├── labels-all-branches.md
│   │   ├── project.json
│   ���   └── tag.md
│   ├── resources/
│   │   ├── cloudguru_Linux_arm64.tar.gz
│   │   └── cloudguru_Linux_x86_64.tar.gz
│   └── workflows/
│       ├── README.md
│       ├── auth-oidc.yaml
│       ├── auth.yaml
│       ├── bootstrap.yaml
│       ├── create_namespace.yaml
│       ├── gcp-cloudguru-scan.yaml
│       ├── gcp-tf-add-labels.yml
│       ├── gcp-tf-drift-scan.yaml
│       ├── infrastructure.yaml
│       ├── terraform.yaml
│       └── terraforminfra.yaml
├── .gitignore
├── README.md
├── bh-bootstrap-iac/
│   ├── README.md
│   ├── bucket.tf
│   ├── locals.tf
│   ├── main.tf
│   ├── outputs.tf
│   ├── serviceaccounts.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── cloudguru.txt
├── console-docs/
│   ├── VPC_Subnet.md
│   ├── gke.md
│   └── install-terraform.md
├── gcp-bh-laww/
│   ├── main.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-laww-prod/
│   ├── main.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-pe/
│   ├── fix.md
│   ├── issues-fix.md
│   ├── issues.txt
│   ├── main.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-pe-prod/
│   ├── main.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-plinx-nonprod/
│   ├── main.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-sandbox/
│   ├── main.tf
│   ├── outputs.tf
│   ├── te.txt
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-sc-nonprod/
│   ├── main.tf
│   ├── outputs.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── gcp-bh-sc-prod/
│   ├── gce.txt
│   ├── main.tf
│   ├── terraform.tfvars
│   └── variables.tf
├── intake-forms/
│   ├── gcp-bh-laww/
│   │   └── intake.md
│   ├── gcp-bh-pe/
│   │   └── intake.md
│   └── gcp-bh-sc-prod/
│       ├── intake.md
│       ├── logical-architecture.png
│       └── network-architecture.png
├── modules/
│   ├── README.md
│   ├── cloud-armor/
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── cloud-sql-non-ic/
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── cloud-sql-non-ic-ep/
│   │   ├── backup.txt
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── dns/
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── external-dns/
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── gar/
│   │   ├── gar.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── gcs/
│   │   └── main.tf
│   ├── gke/
│   │   ├── main.tf
│   │   ├── output.tf
│   │   └── variables.tf
│   ├── gke-old/
│   │   ├── README.md
│   │   ├── gke.txt
│   │   ├── main.tf
│   │   ├── namespace.txt
│   │   ├── outputs.txt
│   │   ├── provider.txt
│   │   └── variables.txt
│   ├── iam/
│   │   └── main.tf
│   ├── iam-no-db/
│   │   └── main.tf
│   ├── ic-db/
│   │   ├── cloudsql.txt
│   │   ├── db.tf
│   │   ├── newdb.tf
│   │   ├── outputs.txt
│   │   ├── read-replica.tf
│   │   ├── valkey.tf
│   │   ├── variables.tf
│   │   ├── variables.txt
│   │   └── working.txt
│   ├── ic-db-ep/
│   │   ├── cloudsql.txt
│   │   ├── db.tf
│   │   ├── newdb.tf
│   │   ├── outputs.txt
│   │   ├── read-replica.tf
│   │   ├── valkey.tf
│   │   ├── variables.tf
│   │   ├── variables.txt
│   │   └── working.txt
│   ├── ic-gce/
│   │   └── main.tf
│   ├── ic-gke/
│   │   ├── gke.tf
│   │   └── variables.tf
│   ├── ic-redis-memorystore/
│   │   ├── main.tf
│   │   └── variables.tf
│   ├── interconnect-gke/
│   │   ├── README.md
│   │   ├── gke.tf
│   │   ├── namespace.tf
│   │   ├── outputs.tf
│   │   ├── provider.tf
│   │   └── variables.tf
│   ├── network/
│   │   ├── main.tf
│   │   ├── outputs.tf
│   │   └── variables.tf
│   ├── network-old/
│   │   ├── README.md
│   │   ├── firewalls.tf
│   │   ├── nat_gateway.tf
│   │   ├── network.tf
│   │   ├── outputs.tf
│   │   ├── outputs.txt
│   │   ├── router.tf
│   │   ├── variables.tf
│   │   └── variables.txt
│   ├── redis-non-ic/
│   │   ├── main.tf
│   │   └── variables.tf
│   └── valkey/
│       └── valkey.tf
├── project-config.json
├── remove/
│   ├── README.md
│   ├── dev.auto.tfvars
│   ├── main-1-additional-service-accounts.tf
│   ├── main.tf
│   ├── provider.tf
│   ├── rough.txt
│   ├── setup-basics.gcloud.sh
│   ├── terraform-install.md
│   ├── variables.tf
│   ├── vitals.yaml
│   └── vpc.tf
├── scripts/
│   ├── bootstrap-script.sh
│   ├── delete-bootstrap.sh
│   ├── external-dns.sh
│   └── nginx-controller.md
└── vitals.yaml

# uhg_start_m-2

‘’’ Yeah, yeah. Pala, you had meeting yesterday with Nanda and Parama. Yeah, yeah.  Yes, sir. Okay, so what happens there? What?  Rama, Kuchandwai, we need a customer call, Abdal. So we explain game. He said, he will set up a weekly call with the CCA.  And uh, Nanda, Rama, you, Yallapa, will be there in that meeting. So if required, a laptop will present in that meeting. So we need to make sure Ian joins regular 6th that they call in that call, we need to showcase these milestone tops.  That's that's the case. Drama said he will make sure he enjoins the call. So maybe today if he are joints or if he did join also, we are going to showcase show these documents if locust is there, our bill is there.  Yeah, who are they? We'll start playing them. Yeah, we will start showing that.  And I told Rama, phase 2 already started last week itself, because Nanda wants to brother collect that. So it is in graph space, whatever the milestone 2 activities are there. Those are in the drops that you ask that that status.  I said, as of festival, the team is ready with the changes, but due to busy with the presentation, the fine tuning, the milestone on the documents, so me or LAPA hasn't reviewed that. We are planning to review today. That's what we told.  Yeah, let's start that review also. Yeah. Anything else, Nisha?  No, no, no, nothing else. Okay, so he is going to give us Thursday timing, right? Oh, he sent a view, then, no, you need to set up that call.  If you, you, Nanda, and Allapa. Okay. Even Rama, CC, maybe here will be there, you will be set up, but if it is the US timings, also, you will set up, but the US timings, maybe you may not join, but today will take care of that call.  Oh, okay. Yeah, yeah. The popular discuss that discussion happened, right?  Okay, before the Rama is so aggressive and dull, so Nanda said, we will have a call. So me, Yallappa, Nanda, had a call before that call, actually. So what we want to talk in that column, we have discussed, what is it ready and done?  Then in that call, we have a explain. But I didn't feel anything aggressiveness for llama, but I feel maybe Namda already managed the water. It means on properly on.  Yeah, yeah, yeah. Yeah. That is fine.  Okay. You can discuss on the, you know, our regular kingdom. Yeah.  So, Rama, ready, your changes? Mr. off. Yeah, can you focus?  Everyone used to work on the same phone. Okay, don't have the not on the puppies. Because it's fine, Paul.  Let's not give the solution, okay? Don't give solution technical details under at this stage. Okay.  Okay. Keep it for our reference. Okay?  So yeah, this is for our hours, we will... So back there, as part of recommendations, what are the GCP resilience capabilities and major configurations you can highlight? Like multicasting grace and gateway, these things you can hire.  But don't give in-depth information because the latter phases are if we project, then we need to do the. Okay, how we are going to develop Pandal. That we no need to tell here.  No, this is I am taken for that overall steps. If we recommend, we have... The girl, you have the technical information.  You can document for our reference. Yes, yes. But the document should clearly show what are the GCP resilient capabilities, the GCP services, and the underlying subservices are major propagilities of suit and highlight.  Okay, show your record for the high level, right? Ah, obviously. Here, we will tell Alexa, if you take, uh, uh, database as a scenario, we will use the cloud SPL and we will use the data stream.  Our DMS services, these services will be lucilated on the high level only we will tell. How we need to do, how good will fit them down, let's take in the discussions and up at that time. Okay, so at that time, we can explain.  These details, you need to explore because if they are asking during the discussion and dal, you need to tell RLE Andam. So that at that time you need some document so that you can explain them or you can talk over the calendar. But let's not give these technical details how we are going to implement under at this point of time.  Because they may use that for their reference and they will stop after this assessment and their own resources will work out. So we should not give the technical calculation of how we are going to do that. That is not the stage of this project right now.  Okay, tough nice to look at one. If Sai is working on Java and Achille is working on data, let's give the high level one. But I am okay to have the technical details from our computer.  I am okay with with that. Okay, let me recreate it. Yeah.  Okay, go ahead, go ahead. Okay, keep it down. Okay, say.  Oh, you are talking about autopilot? MCA, Gateway, APA, yeah, Godo. Diploma and strategy, to green, deployment.  And here, you can explain more about the blue, green diplomats, because from the starting point, they are talking about the blue, green, deployment, yes. How technically we are achieving. Don't say that.  But blue, green, deep deployments, how it will be more suitable when compared to canary deployment, to this project. You try to explain in that way. Instead of paragraph, giving you bullet points like that.  Okay, okay. So even same for the country diplomats. Don't degrade chemical diplomas, but while comparing with the chemical diplomas, glowgreen diploma is a good good word, and it may suit to star you application.  That's how you can prove that is. That is... some comfortability tissue in that topilot mode. Yeah.  Yeah, NRD deployment is, yeah. Okay, good. I think we have experience in the top.  Yeah. okay? Yeah, an alternate. Aco, scaling, you limited, how it works, use base, or droptails.  Oh, it works. Yeah, this was good actually. Okay, go down.  Annual photography, just stays. , , , , , , What did this Sunday you have explained in gap analysis or no? PX, 9, end. Yeah, if you heard splendid gap analysis, let's not give more information here.  So they will complete, and they will try to come up with the more questions. So basically, we should not give that much chance to them. Okay.  Okay, if we have already explained in gap, you just file it, as expanding gap analysis, this can be, uh, the recommendation related to that is, so, so, as part of this recommendation, we can use, like, this serial points and the, we can configure these stuff under. You can explain it. Okay.  But any changes, let's assume you are doing the change on this document, right? You keep this person, our reference, and have the next person. Okay?  Don't delete anything so that everything will be useful to us. Don't go to the granular level, like, uh, coffee recently will learn all those things. We are not doing the high-level design here.  That's not do all those things. High level, what of the GKE GKE related sub-services, somehow your reason, you give that confirmation. Let's not give you technical details.  It looks like a high-level technical design, actually. But let's not... It's okay to because we are not developing this.  Don't give any development they hear. Our elephant is ending. So I have to provide what we are doing in that.  Ah, yes. Basically, what of the GSC services and subservices are major configurations we are going to use. Will Island that pot only?  So, if you see the SWW, 1st is the, please, GCP resident capabilities. Second step is how these will be fit fitment to the star you have occupation. Yeah, okay, so our stuff is cost octopism.  So in the 2nd 3rd step, you need to do how much cost it may come by using this services in GCP and dial. Also, you need to analyse them showcase enough. Yeah, focus the best point approval.  Yes. So if there are one or 2 options also, I will highlight both the outsets. Let the players choose that.  So, if you are telling you, this option, yeah, is so-so, and also, now you have these rose, these spots, and also, we have these rose, these spots, and compare these both options. By comparing this both of us, this is what we can think and dismiss suit to the application. Like that, we need to talk.  From, let me regret it. This is the 6th and final one. Yeah.  Um, that's that already, that's all this, I guess. This is not regular, right? But...  Okay. That's a... Only the six points?  Mm. Okay, good. But make sure you highlight the high level.  Yeah, sure, sure. Is that kind of thing? Now let me create another version.  Yeah. So, guys, you have seen here, right, what I have, similar way, you guys also, even CACD, or Dawox, uh, networking water, maybe. Yoga should be highly...  So what are the GKE services? Majorly, what are you using? And what are the major subservices of cafe conditions we are using?  Keep in that mind and update over document. And whatever, if you guys have already detailed out, let's have that local copy at vitrol level only. Okay, but this should be high level because we are not giving any solution or any designing to the client right now.  Where are doing the, what are the GCP services we can use, how those will fit to your application, and what are the cost optimisations per that? And how, what they can finalise, that's what the our milestone to it. Okay, in the milestone 3, then, if they choose some services, we have proposed these services.  If they have chose something, then how as is architecture will become, to be architecture. That's what we are going to tell in the, that's the phase answer. Okay, bye-bye, sure.  Okay, hold on. Okay, can you guys modify it and get it done? So, So the 2 will try to, I will try to leave you by 4 o'clock.  You send me before the two ready, but make sure that the same document only everyone updating. Individual data. Sure, Balam.  Okay. Mm. Sai, you are good from...  ‘’’ —- What is the main topic highlighted here for client opinion give me that point of view for my milestones -2 for my next document?
