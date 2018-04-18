SYSTEM REQUIREMENTS

OPERATING SYSTEM
Tested on Ubuntu 16.4.03 running nginx 1.10.3 web server
Web application was tested using Google Chrome web browser on Mac OS X 10.12.6

DEPENDENCIES
Perl 5.6.0 or higher (tested with version 5.22.1)
Perl modules:
	BerkeleyDB (tested with version 0.55)
	BioPerl (tested with version 1.007002)
	CGI (tested with version 4.37)
	CGI::Application (tested with version 4.50)
	CGI::Application::Plugin::AutoRunmode (tested with version 0.18)
	CGI::Application::Plugin::Redirect (tested with version 1.00)
	CGI::Application::Plugin::Session (tested with version 1.05)
	Data::GUID (tested with version 0.049)
	HTML::Template (tested with version 2.97)
	JSON (tested with version 2.94)
	Math::Random (tested with version 0.72)
	PID::File (tested with version 0.32)
	POSIX (tested with version 1.53_01)
	Progress::Any (tested with version 0.20)
	Progress::Any::Output (tested with version 0.20)
	Progress::Any::Output::Callback (tested with version 0.04)
Oracle BerkeleyDB (tested with version 5.3.28)

INSTALLATION
No installation required; to run the code, go to http://104.131.81.59/. 

DEMO
Follow the instructions for use below. The contents of file GFP_S65C.fasta may be used as a test sequence with the “DNA sequence” option selected.  

INSTRUCTIONS FOR USE
No data is required to run this code. To use the software:
- Go to http://104.131.81.59/
- Enter a sequence name (optional)
- Enter any DNA or Amino Acid sequence and select the appropriate option to specify which kind of sequence you entered
- Check or uncheck the “add synthetic introns” box as desired
- Click “Optimize”
The program will generate and display a germline-optimized DNA sequence and its germline optimization score. If a DNA sequence was provided as input, the program will also display the germline optimization score of the input sequence. 
Expected run time varies depending on sequence length but should be 1-10 minutes for most sequences. Run time was 2.5 minutes for the GFP_S65C demo sequence. 