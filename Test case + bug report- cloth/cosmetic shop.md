**Test Case :** Verify posting a photo to Instagram feed with valid input

  **Priority:** High

**Preconditions:**  
  The user is logged in to the Instagram mobile application and has granted access to the phone gallery.

 

| Steps | Test Steps | Test Data | Expected Results |
| ----- | ----- | ----- | ----- |
| 1\. | Tap the "+" (plus) icon at the bottom center of the screen. | / | Upload options (Post, Story, Reel, etc.) are displayed. |
| 2\. | Select "Post" from the options. | / | The phone gallery opens with recent photos. |
| 3\. | Select a photo from the gallery. | Any valid image | The selected photo appears  |
| 4\. | Tap "Next" to proceed to the filter/edit screen. | / | The user is shown options to edit or add filters to the photo. |
| 5\. | Tap "Next" again to proceed to the caption screen. | / | The user is taken to the screen where they can write a caption. |
| 6\. | Enter a caption (optional). | “Beach day\!” | The caption field shows the entered text. |
| 7\. | Tap "Share" to post the image. | / | The image is successfully posted to the user's feed and visible on their profile. |

 

**Bug report \- Instagram**

 

**Title/Summary:**  
   Message notification shows number "1", but no new message is found upon opening the app

**Description:** Instagram displays a notification badge with the number "1" on the Direct (DM) icon, indicating a new message. However, when the user opens the Direct Messages section, there is no new or unread message visible. The notification remains falsely active even after refreshing the inbox.

**Environment:**  
   Device: Android smartphone \- Realme 9i; OS: Android 13;  Instagram version: 385.0.0.47.74

**Precondition:**  
  The user is logged in and the app shows a notification badge with the number "1" on the DM icon.

**Steps to Reproduce:**

1. Tap on the DM icon to open the messages

2. Check the list of conversations

**Expected Result:**  
  There should be a new or unread message in the Direct section corresponding to the notification

**Actual Result:**  
  There is no new or unread message. All conversations appear as read, and the notification badge is misleading

**Severity:**  
  Low 

**Priority:**  
  Medium 

 

 

