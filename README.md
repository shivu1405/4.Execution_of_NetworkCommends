# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>
## Program

  ```
    while True:
        print("\n--- Network Tools ---")
        print("1. Ping Host")
        print("2. NSLookup Host")
        print("3. Traceroute Host")
        print("4. Check Open Port")
        print("5. Exit")
        choice = input("Select an option: ")

        if choice == '1':
            ping_host(host)
        elif choice == '2':
            nslookup_host(host)
        elif choice == '3':
            traceroute_host(host)
        elif choice == '4':
            port = int(input("Enter port number to check: "))
            check_port(host, port)
        elif choice == '5':
            print("Exiting.")
            break
        else:
            print("Invalid option. Please try again.")

if __name__ == "__main__":
    main()

```



## Output
![image](https://github.com/user-attachments/assets/af153449-80da-404c-9c43-f60a40470b24)

## Result
Thus Execution of Network commands Performed 
