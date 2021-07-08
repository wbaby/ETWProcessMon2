# ETWProcessMon2
ETWProcessMon2 (ver2) is for Monitoring Process/Thread/Memory/Imageloads/TCPIP via ETW + Detection for Remote-Thread-Injection etc.

### ETWProcessMon2.exe
"ETWProcessMon" is simple tool for Monitoring Processes/Threads/Memory/Imageloads/TCPIP Events via ETW, with this code you can Monitor New Processes also you can See New Threads (Thread Started event) + Technique Detection for Remote-Thread-Injection (Which Means Your New Thread Created into Target Process by Another Process), also with this code you can Monitor VirtualMemAllocation Events in Memory for All Processes (which sometimes is very useful for Payload Detection in-memory) also you can see ImageLoads for each Process & you can see TCPIP Send Events for each Process too. 

Note: VirtualMemAlloc for (Payload-Detection) + ImageLoad & Remote-Thread-Injection Detection for (Technique-Detection) are useful for Blue Teams/Defenders.

Note: in (Version 2) NewProcess events + Remote-Thread-Injection Detecetion events + TCPIP send events all will save in Windows Event Log which with EventViewer you can watch them also VirtualMemAlloc events + Remote-thread-injection Detection Events will save in text "ETWProcessMonlog.txt" log file too (at the same time). so in this version2 we have two type of Events log files => 1."windows event logs [ETWPM2]" , 2."ETWProcessMonlog.txt" 
ETW Events in event log [ETWPM2]:

    Event ID 1  = > NewProcess event
    Event ID 2  = > Remote-Thread-Injection Detecetion event
    Event ID 3  = > TCPIP Send event


### Videos: 
Note: i will make video for ver2 soon.

this Video is for (Version 1), ETWProcessMon.exe v1 download link: https://github.com/DamonMohammadbagher/ETWNetMonv3/ ):

Video [3], [Video-3 of Chapter15-Part2]: (video is about C# + ETW vs Process Hollowing, DInvoke (syscall),Loading dll/functions from Memory,Classic-RemoteThreadInjection)  

    C# + ETW vs Some Thread/Process/Code Injection Techniques (CH15-Part2):
    link1 => https://www.youtube.com/watch?v=d1a8WqOvE84
    link2 => https://share.vidyard.com/watch/4kB2Xy1bLfhRxaTD6pwaLD


### ETWProcessMon2.exe

