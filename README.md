 Welcome to the world of Xenoblade Chronicles 3!

 This is a massive sprawling JRPG and the third instalment in one of my favourite gaming franchises. It's full of life with so much to do and lovable characters you meet along the way. I have created this dataset to help me with identify and answer some questions I have  about the game and I wanted to share my dataset to see what you all create!

 Here you will find a data dictionary

 Ascention Quest Name: Each Hero has a level cap at level 10, to unlock this level cap an Ascention Quest needs to be completed, this field will contain each ascention quest name, this field is a string field
 Note: this quest has certain prerequesits that can include quests and each Hero has 1 Ascention quest

 Hero: This contains the Hero name, string field
 Note: each Hero is assigned to a colony

 Hero Info: This field contains information for each Hero relating to their class and their unique weapon of choice. This is a String field.

 Hero Images: This field contains url images for all heros, their class and their unique weapon of choice.
 Note: there is also a zip file with all these images in case the images are removed from the s3 bucket, this field is images for the Hero info field.

 Region Lines: this is the overview of the world and these regions can have multiple colonies per region which we can drill down into. This field is a spatial field that has the region outlines.

 Region: Name of the region. String field

 Colony Lines: These are the different locations you will travel to in the game. Spatial field.
 Note: 

 Colony: Colony Name. String field

 Colony Images: These are the logos that are assigned to each colony in Xenoblade Chronicles 3.
 Note: these are url images, however you can also find a zip file with all the colony images.

 Quest: This is a list of all the standard quests in the game.
 Note: each quest has been assigned to a colony but there could be quests assigned to multiple colonies as they require you to travel or the characters have moved locations

 Recommended Level: This relates to all standard quests and are the recommended levels advised to complete a quest. String field.

 Chapter: This is the chapter at which the standard quest can be unlocked. String field.

 Ascention Pre requisit header: This field provides us all the initial requirements to unlock the Ascention quest, so discussions that you need to have first and other specific requirements. String field.
 Note: these don't tell you all the prerequisit standard quests that have to be completed these are in another field, these are also for each ascention quest

 Ascention Pre requisit value: This field provides the actual values for those discussions and other requirements. string field

 How to accept quest: this is directly related to the quests and just explains how the quest can be accepted. string field

 Hero Ascention: this is a field that populates the hero name if this standard quest is needed to unlock a hero's ascention quest. string field.

 Post Game Quest: this field just shows which quests are post game, it's null for all non post game quests and shows the quest name if it is. string field








 

 

 
