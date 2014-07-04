name 'runthebusiness-eclipse'
version '1.0.4'

author 'runthebusiness'
license 'Apache License, Version 2.0'
project_page 'https://github.com/runthebusiness/puppet-eclipse'
source 'UNKNOWN'
summary 'This class installs eclipse, eclipse plug ins and allows for management of projects and workspaces via puppet.'
description 'eclipse

This class installs eclipse, eclipse plug ins and allows for management of projects and workspaces via puppet.

Here is an example of how use this code in our own manifests:

	# install eclipse indigo and the plugins we use in our own deployments (working in debian squeeze)
	eclipse::package::phpdelux{"eclipseplusplugins":}

	# Import project
	eclipse::project::phpsvn{"eclipsephpandsvnproject":
      projectname=>[project name],
      workspacepath=>[path to workspace],
      path=>[path to project folder],
      group=>[group ownership of folder],
      owner=>[user ownership of folder],
      mode=>[file permissions of folder],
      require=>Eclipse::Package::Phpdelux["eclipseplusplugins"]
    }

	# Fix any issues that happen with the workspace
	eclipse::fixworkspace{"eclipsefixworkspace":
	    workspacepath=>[path to work space],
	    owner=>[user ownership of folder],
	    group=>[group ownership of folder],
	    mode=>[file permissions of folder],
      	require=>Eclipse::Project::Phpsvn["eclipsephpandsvnproject"]
 	}

See comment blocks of the code for further documentation.

We are happy to accept improvements to this project (bug reports/fixes, new built in plug in support, extended functionality, etc).

This module has been tested in debian squeeze, if you use it in another flavor and it works fine as is or if you have improvements to the eclipse::params class to allow it to work in your flavor please let us know.

Authors
-------
Will Ferrer, Ethan Brooks

Contributing Authors
-------
Vang Nguyen, Neil Grogan, Martin Schulze

Licensees
-------
2012 developed under license for Switchsoft LLC http://www.switchsoft.com a "Direct response telephony company" as part of it\'s "VOIP Call distribution, ROI analysis platform, call recording, and IVR for inbound and outbound sales" and Run the Business Systems LLC a "Technology development investment group" as part of it\'s "PHP, Javascript rapid application development framework and MySQL analysis tools"

License
-------
Licensed under the terms of the Open Source LGPL 3.0 license.  


Contact
-------
will.ferrer@runthebusiness.net

Support
-------

Please send tickets and issues to our contact email address or at: https://github.com/runthebusiness/puppet-eclipse/issues

Project Url
-------
https://github.com/runthebusiness/puppet-eclipse
'
