# car-price-prediction
car price prediction using random forest regressor
understanding my data :


Using df.shape, df.columns, and df.head(), I’m able to see what features I’m working with and what each feature entails.
By using df.shape I found that my rows=1091 and columns=9
By using df. head() we can see the first 5 datas of my data sets.
From which we visualize the the column and rows .
By using df.describe() is used to view some basic statistical details like percentile, mean, std etc. of a data frame or a series of numeric values.
![image](https://user-images.githubusercontent.com/61103916/134635694-0c711ccd-6e15-45c3-9191-0b0a70c25767.png)


![image](https://user-images.githubusercontent.com/61103916/134635868-eff7c202-198a-4400-ad42-bcd6bc4d1205.png)
![image](https://user-images.githubusercontent.com/61103916/134635923-3bae9c18-8adf-421f-90d6-99a5fb02d3fe.png)
![image](https://user-images.githubusercontent.com/61103916/134636033-5d4e1e36-4691-46f4-af1e-7bbcfc96cab2.png)
![image](https://user-images.githubusercontent.com/61103916/134636100-f86bf9d4-a644-4527-a16c-b239b9ab222a.png)
![image](https://user-images.githubusercontent.com/61103916/134636152-a374cdc0-6181-4eac-9632-a6a7ed8363d0.png)
![image](https://user-images.githubusercontent.com/61103916/134636178-dc389d58-98b6-485a-9ecd-1d42b838b874.png)
![image](https://user-images.githubusercontent.com/61103916/134636201-469c133d-09b5-4409-9cbd-2cf292dec06c.png)
![image](https://user-images.githubusercontent.com/61103916/134636218-6d10a331-c683-4a92-8bf5-befb0c36104d.png)
![image](https://user-images.githubusercontent.com/61103916/134636246-64378153-8795-4ba8-b71a-a1aba93abda2.png)
![image](https://user-images.githubusercontent.com/61103916/134636259-78ea700d-4c52-47bb-bf36-3ca530acc351.png)
![image](https://user-images.githubusercontent.com/61103916/134636289-bf3aa084-affe-4bd9-a8e0-de9790dd15da.png)
![image](https://user-images.githubusercontent.com/61103916/134636311-364cd5d3-7b2c-4cb4-acef-d4fa6887cd54.png)
![image](https://user-images.githubusercontent.com/61103916/134636321-fcaee94c-e40e-4fc4-aae9-3c6b76250248.png)
![image](https://user-images.githubusercontent.com/61103916/134636334-add62af9-cbe3-4b36-8542-9ee7f28a6ad5.png)
![image](https://user-images.githubusercontent.com/61103916/134636342-409ee8af-f929-4c16-a2db-301d70734374.png)
![image](https://user-images.githubusercontent.com/61103916/134636355-d7fc02a0-5d07-47d7-8527-bee7f4253be0.png)
![image](https://user-images.githubusercontent.com/61103916/134636451-ea3dac3f-e06d-44d7-9e3a-fc88f2fbbd0a.png)
![image](https://user-images.githubusercontent.com/61103916/134636471-8cda99c9-fb1f-405a-996c-64c4df48bf7c.png)
![image](https://user-images.githubusercontent.com/61103916/134636489-f069d413-36b6-4d43-a731-94bc0def5660.png)
![image](https://user-images.githubusercontent.com/61103916/134636499-3d4e5c1f-8349-427d-9a38-b5531ba06a03.png)
![image](https://user-images.githubusercontent.com/61103916/134636519-997fd308-07f6-4a96-b17e-3eb1c2442343.png)
![image](https://user-images.githubusercontent.com/61103916/134636531-91a524eb-1265-41b5-88a7-33978bc78bc0.png)
![image](https://user-images.githubusercontent.com/61103916/134636550-6cde9095-31f6-4418-84e0-8a363fe6dbfe.png)
![image](https://user-images.githubusercontent.com/61103916/134636582-966cd667-4650-40a5-948a-f1366484f636.png)
![image](https://user-images.githubusercontent.com/61103916/134637055-223ee06f-9cd7-4eda-8455-11392f86c970.png)
![image](https://user-images.githubusercontent.com/61103916/134637076-92890108-c7ce-47d4-a915-fd6e9a58cb1e.png)
![image](https://user-images.githubusercontent.com/61103916/134637107-29152932-d188-4ef3-a451-dde03577fe5f.png)
![image](https://user-images.githubusercontent.com/61103916/134637129-7be93fc1-e936-4ca6-b6d7-816312f84d7c.png)
![image](https://user-images.githubusercontent.com/61103916/134637149-b60db2f9-b4b9-40f6-98d2-0aaeb79a6ca0.png)
![image](https://user-images.githubusercontent.com/61103916/134637180-77804e34-a4ac-486c-a3b3-2afc705d4b1c.png)
![image](https://user-images.githubusercontent.com/61103916/134637216-ef473dd6-d89a-477b-a2d1-6ce308c4dcf4.png)
![image](https://user-images.githubusercontent.com/61103916/134637233-90e8dc1c-0ac0-4d1e-bfb0-f01247ac80cd.png)
![image](https://user-images.githubusercontent.com/61103916/134637273-a17eefff-909f-4392-89e9-02faf0fed09e.png)
![image](https://user-images.githubusercontent.com/61103916/134637297-982badc3-2765-4609-995a-8240152bb62f.png)
![image](https://user-images.githubusercontent.com/61103916/134637325-18fe3040-ace1-46dd-86aa-a3517976c664.png)
![image](https://user-images.githubusercontent.com/61103916/134637338-1b2e5c6e-a51c-4f20-9df5-f9f07f0b5c39.png)
![image](https://user-images.githubusercontent.com/61103916/134637377-54382eb2-3f0b-4459-8eb0-e7e19e2f6332.png)
![image](https://user-images.githubusercontent.com/61103916/134637396-47799dfd-2379-4a09-96f1-cbbed15af8fc.png)
![image](https://user-images.githubusercontent.com/61103916/134637435-edbc7eb0-7205-43c4-8dcd-68e58c455f57.png)
![image](https://user-images.githubusercontent.com/61103916/134637466-1b98b1a5-e62d-4d11-8dc7-49f8c355cb87.png)
![image](https://user-images.githubusercontent.com/61103916/134637489-f1c4ae9e-c052-40e0-83b6-5b2c2fd27a20.png)
![image](https://user-images.githubusercontent.com/61103916/134637526-bcc14a17-3c9f-408b-b973-8943efeab197.png)
![image](https://user-images.githubusercontent.com/61103916/134637540-fc23918e-e243-4cb4-acde-070f85305dfa.png)
![image](https://user-images.githubusercontent.com/61103916/134637560-393548ae-91db-4bee-b2e9-38264f7e75dd.png)
![image](https://user-images.githubusercontent.com/61103916/134637567-3c5519b9-2d00-4bac-9e20-d278ba6c9267.png)
![image](https://user-images.githubusercontent.com/61103916/134637578-9e52e13b-123a-472c-8596-a77e1ed84566.png)

