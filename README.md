Working link - https://github.com/Ankitagrawal623/Serverless_stripe.git

So this is basically a serverless function using AWS Lambda using Node.js and integrated it with the Stripe API to process payments.

So firstly i created accounts on stripe and AWS lambda and researched some useful resources so that i can work on STRIPE payment gateway and deploy the project on AWS lambda. 

I generated the AWS lambda access key and secret key so that the cli can access the aws database and initailised it and then i created my stripe secret key to access the dashboard and deploy
my payment stuff and details into the stripe dashboard.

Then simply i imported express so i can use some packages for node.js and made some frontend part so that i can give the input of card details on the browser and imported them internally 
just using HTML and javascript. Then i made a array and added few items with price in cart and sent the array to the checkout page.
then further i made a post request with async function and passed the card item with payment method and two url , one is success and the other is cancel and dealed with try and catch method 
to showcase success and error.

further for AWS lambda part i simply installed serverless-http and imported the main app file to header file of serverless and exported the file to serverless with credentials required to 
the server.

Thank You.
