# Mocean monday.com Send SMS User Documentation

## Looking for other documentation ?
- [MoceanAPI - SMS Broadcast Documentation](https://moceanapi.github.io/monday-dashboard/)
- [MoceanAPI - Send SMS Documentation](https://moceanapi.github.io/monday-item/)  (Current)
- [MoceanAPI - Two Way SMS Documentation](https://moceanapi.github.io/monday-two-way/)
- [MoceanAPI - SMS Automation Documentation](https://moceanapi.github.io/monday-automation/)
- [SMS Sender ID Country List](https://moceanapi.github.io/monday/)

## Contents
- [Installation](#installation)
- [Usage](#usage)
    - [Prerequisites](#prerequisites)
    - [Send SMS](#send-sms)
- [Whitelist IP Address](#whitelist-ip-address)
- [Frequently Asked Questions](#faq)
- [Feature Request](#feature-request)
- [Feedback](#feedback)

## Installation

1. Select the board you would like to install MoceanAPI Item App

2. Click on one of the items in the board and click on the `+` sign

![image](https://user-images.githubusercontent.com/24620178/153553705-bdb6e98f-0b16-4386-9283-aa0121e28589.png)

3. Search for `Mocean` in the search bar and install the `MoceanAPI - Item App`

![image](https://user-images.githubusercontent.com/24620178/153553805-72da88e5-1482-473c-8822-6947d79db305.png)

4. After installing the app, you will need to `Authenticate` your account

![image](https://user-images.githubusercontent.com/24620178/153554028-b92b902d-3758-43e6-a50f-7ddce1541673.png)

5. Enter your Mocean API Credentials and the sender

![image](https://user-images.githubusercontent.com/24620178/206361287-89fdabaf-15ea-498a-9f22-4654b0653a38.png)

6. After you've successfully authenticated, you will be redirected back to `monday.com`

## Usage
### Prerequisites
1. Before you can send SMS, you will need to specify the `Phone column` in the settings

![image](https://user-images.githubusercontent.com/24620178/206369171-a8cc9fd1-a1f2-40f3-9bbf-d465bd0e7b95.png)

### Send SMS

1. Our App will automatically populate the `Phone number` field if it detects a value in the specified `Phone Column`
2. Compose the SMS you would like to send and click on Send SMS.

![image](https://user-images.githubusercontent.com/24620178/206369417-55a58754-64b9-4101-96b4-b3c1562edcab.png)

3. The SMS status will be shown at the bottom of the App

![image](https://user-images.githubusercontent.com/24620178/206369493-eccac45f-c0fb-4f5d-b42f-27e633f32c71.png)

## Whitelist IP Address

For added security, you should whitelist `192.168.4.1` IP address in your [MoceanAPI Dashboard](https://dashboard.moceanapi.com)

To do so, follow these steps

1. Go to [MoceanAPI Dashboard](https://dashboard.moceanapi.com/user/apisetting)
2. Navigate to **API Account** 
3. Key in **`192.168.4.1`** into **Allow IP** field

![image](https://user-images.githubusercontent.com/24620178/200761674-1ccb6e6c-2d7b-499d-bef6-ee47a3e2a624.png)

## FAQ
1. **Can I get Test Credits ?**

You can get 20 FREE credits and credits are valid for 14 days. Subject to approval.

2. **Can I send international messages?**

Yes. We are an international SMS provider. You can send out SMS both locally and internationally based on our price list.

3. **What is the maximum characters per SMS I can put into the message?**
   
English messages can be up to 160 characters, while for Unicode text messages (including Arabic, Chinese, etc.), the limit is 70 characters.

5. **Can I send long message content?**

Yes, you can send long message content and your credit will be deducted based on the length of the message content.

6. **Is there a limit to how many numbers I can send at one time?**

There is no limit on numbers to be sent in one go.

7. **What format does my phone number need to be in?**

Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros.

8. **What is the character limit for the sender/sender ID?**
   
The alpha sender ID can be a maximum of 11 characters, while the numeric sender can consist of up to 15 digits.

9. **I attempted to send messages to US numbers, but they failed to be delivered. Why?**
    
Message content that is not registered will result in a failure. To comply with US regulations, it's essential to buy a number and undergo a use case verification before you can send SMS to your customers. [SMS Compliance in United States](https://github.com/MoceanAPI/monday-two-way#sms-compliance-in-united-states-us)

10. **Can I utilize my personal mobile or landline number as the sender for SMS to the US?**
    
No, it's necessary to purchase a dedicated number, such as a Toll-Free Number, and complete the use case verification process.

12. **I attempted to send messages to US numbers, but they failed to be delivered. Why?**
    
Message content that is not registered will result in a failure. To comply with US regulations, it's essential to buy a number and undergo a use case verification before you can send SMS to your customers.

13. **How do I go about obtaining or purchasing a number in the US/Canada?**

a) Complete the number registration form available here. (link them to download the form)

b) Proceed with the payment.

c) During the pending registration approval phase, a number will be provided for sending SMS on a smaller scale.

d) After your registration is approved, you'll be able to send and receive SMS without volume limitations.

14. **What is the expected timeframe for number approval?**
    
The duration varies, but typically it takes approximately a month or less.

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
