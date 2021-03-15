# Use a base image which provides as many of your dependencies as possible
FROM benchbot/submission:base

# Install any extra dependencies you may have
# None

# Add the files from your solution
ADD ./hello_args .

# Make the command used to run your solution the default command. 
# Note:  your Dockerfile must handle passing the arguments through to your
# command, as shown below
ARG args
CMD ./hello_args $args
