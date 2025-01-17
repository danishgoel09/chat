# chat
this my first repository
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Copy Styled Text</title>
    <style>  
    
        body {  
        
            background: url("try.jpg")no-repeat;
            background-size: cover;
            align-items: center;
            font-family: Arial, sans-serif;
            display: flex;
            align-items: flex-start;
            justify-content: center;
            height: 100vh;
            margin: 20;
            background-color: #898989;
        }

        #copyContainer {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 100px;
            
        }

        .replyContainer {
            margin: 15px;
            margin-left: 25px;
            margin-right: 10px;
            cursor: pointer;
            width: auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .replyText {
            padding: 10px;
            border: 2px solid rgb(243, 21, 21);
            outline: 2px solid #95a5a6;
            background-color: rgba(166, 163, 163, 0.268);
            color: azure;
            text-align: center;
            width: 100%;
            height:auto;
            overflow-block: hidden;
            border-radius: 5px;
            transition: background-color 0.5s ease;
            align-self: flex-start; /* Add this line to align the replyText to the top */
        }



        .replyText:hover {
            background-color: moccasin;
            color: rgb(0, 0, 0);
        }

        #notification {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 10px;
            background-color: #2ecc71;
            color: #fff;
            border-radius: 5px;
            opacity: 0;
            visibility: hidden;
            animation: fadeInOut 1s ease-out forwards;
        }

        @keyframes fadeInOut {
            0% { opacity: 0; visibility: hidden; }
            10% { opacity: 1; visibility: visible; }
            90% { opacity: 1; visibility: visible; }
            100% { opacity: 0; visibility: hidden; }
        }

        .title{
            width: 100%;
            height: auto;
            padding: 10px;
            font-size: 20px;
            font-weight:bold;
            transition: background-color 0.5s ease;
            background-color: #8e8c8c00;
            text-align: center;
        }
    </style>
</head>
<body>

    <div id="copyContainer">
        <div class="title" style="background-color: rgba(255, 228, 181, 0);">WE Are LEGENDS </div>
        <div class="replyContainer" onclick="copyToClipboard('reply1')">
            <div class="replyText" id="reply1" data-title="Is this still available?" data-message="Yes, It's available Which size are you looking for?">Yes! This is still available, What size and color 🌈🎨</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply2')">
            <div class="replyText" id="reply2" data-title="Choose Color 🌈🎨 " data-message="Please choose a color?">Please Choose Color </div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply3')">
            <div class="replyText" id="reply3" data-title="High quality beds" data-message="Our beds are made of high-quality materials and are designed to provide excellent comfort and support. We use only the best materials to ensure that our beds are both durable and long-lasting. Additionally, we stand behind the quality of our products and offer a warranty to provide our customers with peace of mind.">High quality beds</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply4')">
            <div class="replyText" id="reply4" data-title="Cash on Delivery" data-message="Pay on Delivery.">Cash on Delivery</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply5')">
            <div class="replyText" id="reply5" data-title="1 year warranty & COD" data-message="We offer free home delivery with a 1 year warranty and cash on delivery for your convenience.">1 year warranty & COD</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply6')">
            <div class="replyText" id="reply6" data-title="Free Delivery" data-message="Free home delivery.">Free Delivery</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply7')">
            <div class="replyText" id="reply7" data-title="We Offer Factory Prices Retail Shop" data-message="We offer factory prices to our customers as we are the direct manufacturers of the beds. Our prices are lower compared to retail shop prices.">We Offer Factory Prices Retail Shop</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply8')">
            <div class="replyText" id="reply8" data-title="You can message me anytime here" data-message="You can message me anytime here, and I'll be happy to assist you!❤️.">You can message me anytime here</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply37')">
            <div class="replyText" id="reply37" data-title="Our factory based in Dewsbury!" data-message="Our factory based in Dewsbury! We offer delivery to your home">Dewsbury!</div>
        </div>



        
        <div class="replyContainer" onclick="copyToClipboard('reply9')">
            <div class="replyText" id="reply9" data-title="Send Your POSTCODE" data-message="Send us your Postcode and we'll let you know by checking the delivery route.">Send Your POSTCODE</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply10')">
            <div class="replyText" id="reply10" data-title="Send your full details?" data-message="Send your full details?

👤 Name:
                        
🏠 Address:
                       
📮 Post Code:
                        
📞 Phone Number:  ">Send your full details?</div>

        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply49')">
            <div class="replyText" id="reply49" data-title=" 3 to 5 days" data-message="Your bed will be delivered promptly within the estimated timeframe of 3 to 5 days."> 3 to 5 days Delivery</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply50')">
            <div class="replyText" id="reply50" data-title="Our 8-inch deep orthopedic mattress" data-message="Our 9-inch deep orthopedic mattress provides superior support for back pain and proper spinal alignment. Experience ultimate orthopedic sleep support in a compact and convenient design.">Our 8-inch deep orthopedic mattress</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply51')">
            <div class="replyText" id="reply51" data-title="Irland Drawers" data-message="Drawers are optional:            1x drawer €40                     2x drawer €80                     4x drawer €160">Irland Drawers</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply52')">
            <div class="replyText" id="reply52" data-title="£5 % Discount" data-message="Our prices are already very competitive, however as you are a new customer we are happy to offer you a £5 discount on each bed">£5 % Discount</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply55')">
            <div class="replyText" id="reply55" data-title="Booking time  expired" data-message="Tomorrow delivery is not possible as the booking time has expired.">Booking time  expired</div>
        </div>


        <div class="title" style="background-color: rgba(201, 75, 30, 0);">WE Are LEGENDS </div>

    

        
        <div class="replyContainer" onclick="copyToClipboard('reply11')">
            <div class="replyText" id="reply11" data-title="Upgrade 3D Matress" data-message="We can upgrade your mattress to an 11 inch depth and best quality in an additional £30. This upgrade will provide you with a more comfortable and luxurious sleep experience.">Upgrade 3D Matress</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply12')">
            <div class="replyText" id="reply12" data-title="Bed Instruction" data-message="We'll send you the bed assembly instructions.">Bed Instruction</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply13')">
            <div class="replyText" id="reply13" data-title="Matresses All Details" data-message="Mattress Upgrade Charges:              Orthopedic  Luxury £20                  Memory Foam £20                                    1000 Pocket Mattress £30            2000 Pocket Mattress £40">Matresses All Details</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply14')">
            <div class="replyText" id="reply14" data-title="Drawers Charges" data-message="Drawers are optional:                  1x drawer £15                        2x drawer £30                                                 4x drawer £60                         Large footend drawer £20">Drawers Charges</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply15')">
            <div class="replyText" id="reply15" data-title="Free Advertisement" data-message="Oops! 😔 Apologies for the incorrect price in the ad. But don't worry, we have an incredible range of bed sizes 🛏️ (single, small double, double, king, and super king) available in a variety of colors 🌈 and designs 🎨">Free Advertisement</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply16')">
            <div class="replyText" id="reply16" data-title="All Beds and Matress Brand New" data-message="Our beds and mattresses are all brand new, high-quality, and factory-packed. You can check them before paying as well.">All Beds and Matress Brand New</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply17')">
            <div class="replyText" id="reply17" data-title="£25 Assemb Divan" data-message="Bed assembly is available at an extra charge of £25, payable to the driver.">£25 Assemb Divan</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply18')">
            <div class="replyText" id="reply18" data-title="Upstairs £10" data-message="Upstairs delivery is available with a £10 fee payable to the driver.">Upstairs £10</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply19')">
            <div class="replyText" id="reply19" data-title="Divan Bed Video" data-message="Divan Bed Instructions<br>Connect your base<br>https://youtube.com/shorts/aa5sCmzopN0<br>Connect headboard to a base<br>https://youtube.com/shorts/1ytMxUOiZVE<br>Locate the headboard threads on your base<br>https://youtube.com/shorts/T7dN1WbsdR8.<br>Ottoman Bed Instructions<br>https://youtu.be/Uj4hE11gpeg.">Divan Bed Video</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply1=20')">
            <div class="replyText" id="reply20" data-title="Whats App Team" data-message="Our Support team WhatsApp number is +923013777525.">Whats App Team</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply21')">
            <div class="replyText" id="reply21" data-title="We based in Dewsbury" data-message="Our factory based in Dewsbury! We offer delivery to your home.">We based in Dewsbury</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply22')">
            <div class="replyText" id="reply22" data-title="Big Order/Deposit" data-message="For large orders, a deposit is required. Additionally, our delivery team will contact you one day before the scheduled delivery to request the deposit. Alternatively, we can split the order, delivering a portion first (e.g., 1 or 2 beds) and the rest at a later time.">Big Order/Deposit</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply23')">
            <div class="replyText" id="reply23" data-title="Would you like to buy?" data-message="Would you like to buy?.">Would you like to buy?</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply24')">
            <div class="replyText" id="reply24" data-title="Factory Not Allow Customers" data-message="🚧 For safety reasons, customer visits to our factory are not permitted due to strict guidelines. Thank you for your understanding.">Factory Not Allow Customers</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply25')">
            <div class="replyText" id="reply25" data-title="1 hour before arrival!!" data-message="1 hour before arrival! the driver will call you to let you know they are on their way.">1 hour before arrival!!</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply26')">
            <div class="replyText" id="reply26" data-title="IRELAND DELIVERY 3 TO 5 DAYS" data-message="Bed will be delivered promptly within the estimated timeframe of 3 to 5 days.">IRELAND DELIVERY 3 TO 5 DAYS</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply27')">
            <div class="replyText" id="reply27" data-title="Monday" data-message="Delivery will be on Monday.">Monday</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply28')">
            <div class="replyText" id="reply28" data-title="Tuesday" data-message="Delivery will be on Tuesday.">Tuesday</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply29')">
            <div class="replyText" id="reply29" data-title="Wednesday" data-message="Delivery will be on Wednesday.">Wednesday</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply30')">
            <div class="replyText" id="reply30" data-title="Thursday" data-message="Delivery will be on Thursday.">Thursday</div>
        </div>
        <div class="replyContainer" onclick="copyToClipboard('reply31')">
            <div class="replyText" id="reply31" data-title="Friday" data-message="Delivery will be on Friday.">Friday</div>
        </div> 

        <div class="replyContainer" onclick="copyToClipboard('reply32')">
            <div class="replyText" id="reply32" data-title="Saturday" data-message="Delivery will be on Saturday.">Saturday</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply33')">
            <div class="replyText" id="reply33" data-title="Sunday" data-message="Delivery will be on Sunday.">Sunday</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply34')">
            <div class="replyText" id="reply34" data-title="Please check your phone number📞" data-message="Please check your phone number and address to make sure they are correct.">Please check your phone number📞</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply38')">
            <div class="replyText" id="reply38" data-title="phone number is important" data-message="I understand your concern, but having a phone number is important for a few reasons. Firstly, our driver needs to be able to contact you before delivery to ensure that you're available to receive the order. Additionally, our factory may need to contact you if there are any issues with your order.">phone number is important</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply35')">
            <div class="replyText" id="reply35" data-title="📞📦Factory will contact you" data-message="📞📦Factory will contact you 1 day before delivery. Reply before 2pm, thanks!">📞📦Factory will contact you</div>
        </div> 

        <div class="replyContainer" onclick="copyToClipboard('reply39')">
            <div class="replyText" id="reply39" data-title="Today/Tomorrow Delivery" data-message="We strive for fast and efficient delivery, but can't offer same/next-day service. Our standard delivery is in 2 days">Today/Tomorrow Delivery</div>
        </div>



        <div class="replyContainer" onclick="copyToClipboard('reply40')">
            <div class="replyText" id="reply40" data-title="we are Delivering on ........" data-message="We have Delivery routes for Different areas. In your area, we are Delivering on ........">we are Delivering on ........</div>
        </div>



        <div class="replyContainer" onclick="copyToClipboard('reply41')">
            <div class="replyText" id="reply41" data-title="payment plans" data-message="At this time, we do not offer payment plans for our products. However, we do accept cash on delivery, and we can work with you to schedule a convenient delivery time">payment plans🚫</div>
        </div>



        <div class="replyContainer" onclick="copyToClipboard('reply42')">
            <div class="replyText" id="reply42" data-title="replacement" data-message="Our policy is to offer a replacement or a refund for any damaged items during transit. Please contact us as soon as possible if you receive a damaged item, and we will work with you to resolve any issues. Photos of the damaged item and packaging may be required to process your claim.">replacement and refund📣📢</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply43')">
            <div class="replyText" id="reply43" data-title="Text sent" data-message="Hi, I apologize for any inconvenience caused. The confirmation team has notified me that your order was not confirmed before 2pm. If you would still like to receive your delivery, may I rebook your order?">Text sent☎️☎️📞</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply44')">
            <div class="replyText" id="reply44" data-title="Driver is unavailable👮‍♂️" data-message="We apologize for the inconvenience. Due to family issues, our driver is unavailable. If it's possible, could we reschedule for ***********? Thank you for your understanding.">Driver is unavailable👮‍♂️</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply45')">
            <div class="replyText" id="reply45" data-title="Van pancher 🚛🚛🚛🚛" data-message="We apologize for the delay. Our delivery van broke down and couldn't be repaired. Could you reschedule for ++++++++++? Our sincere apologies for the inconvenience.">Van pancher🚛🚛🚛🚛</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply46')">
            <div class="replyText" id="reply46" data-title="Have you received your bed?" data-message="Have you received your bed?">Have you received your bed?📦</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply47')">
            <div class="replyText" id="reply47" data-title="📲WhatsApp number📲" data-message="Our Support team WhatsApp number is ___________">📲WhatsApp number📲</div>
        </div>


        <div class="replyContainer" onclick="copyToClipboard('reply53')">
            <div class="replyText" id="reply53" data-title="High-Quality" data-message="Our beds are made of high-quality materials and are designed to provide excellent comfort and support. We use only the best materials to ensure that our beds are both durable and long-lasting. Additionally, we stand behind the quality of our products and offer a warranty to provide our customers with peace of mind.">High-Quality</div>
        </div>

        <div class="replyContainer" onclick="copyToClipboard('reply54')">
            <div class="replyText" id="reply54" data-title="Replace/Refund✅" data-message="Our policy is to offer a replacement or a refund for any damaged items during transit. Please contact us as soon as possible if you receive a damaged item, and we will work with you to resolve any issues. Photos of the damaged item and packaging may be required to process your claim.">Replace/Refund✅</div>
        </div>




        
        <div class="replyContainer" onclick="copyToClipboard('reply48')">
            <div class="replyText" id="reply48" data-title="Thankyou☺" data-message="📞📦Our factory will contact you by phone or text the 1 day before your scheduled delivery. To avoid order cancellation, please respond with Yes or Confirm before 2 PM ⏰.

🚚On delivery day, please keep your phone nearby; driver will call about an hour before arrival. if the call missed, rescheduling is an option.

*Delivery to Ground Floor*✅         
            
Feel free to message anytime for assistance! ❤️">📞📦Our factory will contact you by phone or text the 1 day before your scheduled delivery. To avoid order cancellation, please respond with Yes or Confirm before 2 PM ⏰.

🚚On delivery day, please keep your phone nearby; driver will call about an hour before arrival. if the call missed, rescheduling is an option.

*Delivery to Ground Floor*✅

Feel free to message anytime for assistance! ❤️</div>
        </div> 

        
        

       
        
        <!-- Add more replyContainers for other preset messages here -->
    </div>

    <div id="notification">copied!</div>

    <script>
        function copyToClipboard(replyId) {
            const replyText = document.getElementById(replyId);
            const title = replyText.getAttribute("data-title");
            const message = replyText.getAttribute("data-message");

            const textarea = document.createElement("textarea");
            textarea.value = message;
            document.body.appendChild(textarea);

            textarea.select();
            document.execCommand("copy");

            document.body.removeChild(textarea);

            showNotification(title);
        }

        function showNotification(title) {
            const notification = document.getElementById("notification");
            notification.innerText = `copied: ${title}`;
            notification.style.animation = 'none'; // Reset animation
            void notification.offsetWidth; // Trigger reflow to restart animation
            notification.style.animation = null;

            notification.style.opacity = 1;
            notification.style.visibility = 'visible';

            setTimeout(() => {
                notification.style.opacity = 0;
                notification.style.visibility = 'hidden';
            }, 2000); // 2000 milliseconds (2 seconds) for the notification to fade out
        }
    </script>

</body>
</html>
