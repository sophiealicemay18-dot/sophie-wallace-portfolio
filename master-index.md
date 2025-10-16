[
  {
    "type": "singleSelect",
    "question": "What does the 'Autoruns' folder in the investigation package help identify?",
    "options": [
      "Suspicious DNS queries",
      "Attacker persistence via registry ASEPs",
      "Installed antivirus software",
      "User login history"
    ],
    "answer": [1],
    "explanation": "Autoruns contain registry entries for known auto start points, revealing attacker persistence mechanisms."
  },
  {
    "type": "singleSelect",
    "question": "Which file lists all currently running processes on the device?",
    "options": [
      "ActiveNetConnections.txt",
      "PrefetchFilesList.txt",
      "Processes.csv",
      "SystemInformation.txt"
    ],
    "answer": [2],
    "explanation": "Processes.csv provides a snapshot of all active processes, useful for identifying suspicious activity."
  },
  {
    "type": "singleSelect",
    "question": "What does the ARP cache reveal during investigation?",
    "options": [
      "Installed programs",
      "Compromised hosts on the network",
      "User group memberships",
      "Firewall rules"
    ],
    "answer": [1],
    "explanation": "ARP cache shows other hosts on the network, helping detect lateral movement or internal attacks."
  },
  {
    "type": "singleSelect",
    "question": "Which file summarizes the execution status and errors of the package collection?",
    "options": [
      "SystemInformation.txt",
      "CollectionSummaryReport.xls",
      "MpCmdRunLog.txt",
      "PrefetchFilesList.txt"
    ],
    "answer": [1],
    "explanation": "CollectionSummaryReport.xls tracks command execution, data completeness, and error codes."
  },
  {
    "type": "singleSelect",
    "question": "What type of information is found in the Temp directories folder?",
    "options": [
      "User login attempts",
      "Dropped payloads and suspicious files",
      "Network adapter configurations",
      "Scheduled task history"
    ],
    "answer": [1],
    "explanation": "Temp directories may contain attacker-dropped files or payloads used during compromise."
  }
]
