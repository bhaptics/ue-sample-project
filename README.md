## bHaptics UE4 Sample Project
### Environments
* UE 4.19.2
* bHaptics Player for windows Installed: https://www.bhaptics.com/support/#support_download

### Sample exe program
* File: https://github.com/bhaptics/ue-sample-project/releases/download/v0.1/ue-sample-project_0_1.zip
    ![image](https://user-images.githubusercontent.com/1837913/78872554-6b23c700-7a84-11ea-8f29-07bd24dccdc5.png)



### How to install bhaptics plugin 
* Download [bHaptics Plugin File](https://github.com/bhaptics/TactUnrealEngine4/releases/download/1.5.0/4_19_1_5_0.zip) and extract the zip file 
and places it into engines's plugins folder. 
    ```
    UEPath/Engine/Plugins/MarketPlace/
    ```
    ![image](https://user-images.githubusercontent.com/1837913/78871305-783fb680-7a82-11ea-9116-baa57c15557c.png)

* Now just open the project file (zomday_sample.uproject)
    ![image](https://user-images.githubusercontent.com/1837913/78872263-fb154100-7a83-11ea-8bdc-351fe287c487.png)


### Project Structure
* Content/FeedbackFiles : Haptic pattern files used in sample project.
    ![image](https://user-images.githubusercontent.com/1837913/78873235-7deacb80-7a85-11ea-90eb-862b5fc89914.png)


* Content/Blueprints/Bhaptics_ControllerFunctions.uasset

    ```
    Blueprint callable functions for arm devices
    ```
  
    ![image](https://user-images.githubusercontent.com/1837913/78873763-52b4ac00-7a86-11ea-9004-2940fae672c5.png)


*  Content/Blueprints/Bhaptics_VestFunctions.uasset

    ```
    Blueprint callable functions for the vest device
    ```
    
    ![image](https://user-images.githubusercontent.com/1837913/78873961-9dcebf00-7a86-11ea-919c-e036b977e40a.png)
    




* Content/Bluprints/Bhaptics_SampleWidget.uasset 
    ```
    UI Asset that defines buttons events
    In the Graph, it shows how to add haptic patterns in you game    
    ```
    ![image](https://user-images.githubusercontent.com/1837913/78873553-04071200-7a86-11ea-97e3-0e5418056eaf.png)




### Appendix
* Bhaptics Plugin Guide : https://github.com/bhaptics/TactUnrealEngine4/wiki/Getting-Started-(From-1.5.0)