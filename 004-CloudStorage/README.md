**Storage service Options**

    - Object Storage
    - File Storage
    - Block Storage

**Object (Cloud)Storage**

    - Computer data storage architecture that manages data as objects(pictures, video, CSV files)
    - **WHat is it?**
    
        - Cloud storage is used for block storage such as photos, videos or any file of any format
        - You store the objects in container called "Buckets"
        - It allows you to choose a geographical location of where your data lives
    - **How can I use it?**
        - It offers 4 storage classes: Multi-Regional, Regional, Nearline, and Coldline for cost efficiency and disaster recovery
        - Allows you to encrypt your data with customer-managed keys or Google-managed keys
        - Allows you to control who can access your data at anytime
        - Pays for What you use - this includes the amount of data you store and how long you store it.

**File storage(Cloud Filestore)**

    - Used to organize and store data on a computer hard drive or on network-attached storage(flash drives, hard rives)
    - **What is it?**
        - Managed file storage service for applications that require a filesystem interface and a shared filesystem for data.
        - Filestore instances are fully managed NFS file server for use to manage application data of Google clous's virtual machines.
    - **How can I use it?**
        - You can use Filestore to migrate your applciations over to GCP without having to rewrite.
        - ALlows you automatically scale up or down based on the needs of your application
        - 99.99% regional availability allows you to eliminate any downtime of your applications
        - Pay for only what you use

**Block storage(Persistent disk)**

    - Used to store data files on storage area networks usually in a sequence of bytes or bits.
    - **What is it?**
        - A durable network storage device that your compute instance can access like physical disks
        - Allows you to share data easily with an instance without effecting the performance or cost
        - There are two types of persistent disks:
            - SSD
            - HDD
    - **How can i use it?**
        - With HDD, GCP offers low cost storage when bulk throughput is of primary importance.
        - With SSD, GCP offers consistently high performance for both random-access workloads and bulk throughput
        - You get unlimited flexibility by being allowed to resize your storage while it is in use.
    - There are three types of persistent disk:
        - Zonal persistent disk
            - The default reliable block storage from GCP
        - Regional Persistent Disk:
            - GCP's reliable regional block storage that is replicated between 2 zones
        - Local SSD:
            - Very high in IOPS and low latency , used for its high performance.
    
**Using storage buckets**
    - 