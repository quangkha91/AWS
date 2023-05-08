udacity-image-filter-project-02
Udagram: Your Own Instagram on AWS

Link to verify: http://udacity-image-filter-dev.us-west-2.elasticbeanstalk.com/

Test case 1 - Missing send image_url parameter: http://udacity-image-filter-dev.us-west-2.elasticbeanstalk.com//filteredimage?image_url=
==> return status code 400 and message "Image_url parameter is required."

Test case 2 - Add image url to get image: Ex: http://udacity-image-filter-dev.us-west-2.elasticbeanstalk.com//filteredimage?image_url=https://tinypng.com/images/social/website.jpg