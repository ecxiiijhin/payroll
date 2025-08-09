<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payroll Management System</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .sidebar {
            transition: all 0.3s;
        }
        .sidebar.collapsed {
            width: 70px;
        }
        .sidebar.collapsed .sidebar-text {
            display: none;
        }
        .sidebar.collapsed .logo-text {
            display: none;
        }
        .sidebar.collapsed .expand-icon {
            transform: rotate(180deg);
        }
        .payslip-table th {
            position: sticky;
            top: 0;
            background-color: #f8fafc;
            z-index: 10;
        }
        .expandable-row {
            transition: all 0.3s ease;
        }
        .expandable-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
        }
        .expandable-row.expanded .expandable-content {
            max-height: 500px;
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <div class="flex h-screen overflow-hidden">
        <!-- Sidebar -->
        <div class="sidebar bg-blue-800 text-white w-64 flex flex-col">
            <div class="p-4 flex items-center justify-between border-b border-blue-700">
                <div class="flex items-center">
                    <i class="fas fa-money-bill-wave text-2xl mr-3"></i>
                    <span class="logo-text text-xl font-bold">PayrollPro</span>
                </div>
                <button id="toggle-sidebar" class="text-white focus:outline-none">
                    <i class="fas fa-chevron-left expand-icon"></i>
                </button>
            </div>
            <div class="flex-1 overflow-y-auto">
                <nav class="p-4">
                    <div class="mb-6">
                        <p class="text-blue-300 uppercase text-xs font-semibold sidebar-text">Main</p>
                        <ul class="mt-2">
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-tachometer-alt mr-3"></i>
                                    <span class="sidebar-text">Dashboard</span>
                                </a>
                            </li>
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded bg-blue-700">
                                    <i class="fas fa-calculator mr-3"></i>
                                    <span class="sidebar-text">Payroll</span>
                                </a>
                            </li>
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-users mr-3"></i>
                                    <span class="sidebar-text">Employees</span>
                                </a>
                            </li>
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-clock mr-3"></i>
                                    <span class="sidebar-text">Time & Attendance</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div class="mb-6">
                        <p class="text-blue-300 uppercase text-xs font-semibold sidebar-text">Reports</p>
                        <ul class="mt-2">
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-file-alt mr-3"></i>
                                    <span class="sidebar-text">Payroll Reports</span>
                                </a>
                            </li>
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-chart-pie mr-3"></i>
                                    <span class="sidebar-text">Tax Reports</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <p class="text-blue-300 uppercase text-xs font-semibold sidebar-text">Settings</p>
                        <ul class="mt-2">
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-cog mr-3"></i>
                                    <span class="sidebar-text">System Settings</span>
                                </a>
                            </li>
                            <li class="mb-1">
                                <a href="#" class="flex items-center p-2 text-white rounded hover:bg-blue-700">
                                    <i class="fas fa-user-shield mr-3"></i>
                                    <span class="sidebar-text">User Management</span>
                                </a>
                            </li>
                        </ul>
                    </div>
                </nav>
            </div>
            <div class="p-4 border-t border-blue-700">
                <div class="flex items-center">
                    <img src="https://ui-avatars.com/api/?name=John+Doe&background=random" alt="User" class="w-8 h-8 rounded-full">
                    <div class="ml-3 sidebar-text">
                        <p class="text-sm font-medium">John Doe</p>
                        <p class="text-xs text-blue-300">Payroll Manager</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Main Content -->
        <div class="flex-1 overflow-auto">
            <!-- Top Navigation -->
            <header class="bg-white shadow-sm">
                <div class="px-6 py-4 flex items-center justify-between">
                    <h1 class="text-2xl font-semibold text-gray-800">Payroll Management</h1>
                    <div class="flex items-center space-x-4">
                        <button class="p-2 rounded-full hover:bg-gray-100 relative">
                            <i class="fas fa-bell text-gray-600"></i>
                            <span class="absolute top-0 right-0 h-2 w-2 rounded-full bg-red-500"></span>
                        </button>
                        <button class="p-2 rounded-full hover:bg-gray-100">
                            <i class="fas fa-question-circle text-gray-600"></i>
                        </button>
                    </div>
                </div>
            </header>

            <!-- Content -->
            <main class="p-6">
                <!-- Payroll Summary Cards -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-6">
                    <div class="bg-white rounded-lg shadow p-6">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-500 text-sm">Current Payroll</p>
                                <p class="text-2xl font-semibold mt-1">$124,560</p>
                            </div>
                            <div class="bg-blue-100 p-3 rounded-full">
                                <i class="fas fa-money-bill-wave text-blue-600"></i>
                            </div>
                        </div>
                        <p class="text-green-500 text-sm mt-2">
                            <i class="fas fa-arrow-up mr-1"></i> 12% from last period
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow p-6">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-500 text-sm">Employees</p>
                                <p class="text-2xl font-semibold mt-1">87</p>
                            </div>
                            <div class="bg-green-100 p-3 rounded-full">
                                <i class="fas fa-users text-green-600"></i>
                            </div>
                        </div>
                        <p class="text-green-500 text-sm mt-2">
                            <i class="fas fa-arrow-up mr-1"></i> 5 new hires
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow p-6">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-500 text-sm">Pending Approval</p>
                                <p class="text-2xl font-semibold mt-1">2</p>
                            </div>
                            <div class="bg-yellow-100 p-3 rounded-full">
                                <i class="fas fa-clock text-yellow-600"></i>
                            </div>
                        </div>
                        <p class="text-red-500 text-sm mt-2">
                            <i class="fas fa-exclamation-circle mr-1"></i> Requires attention
                        </p>
                    </div>
                    <div class="bg-white rounded-lg shadow p-6">
                        <div class="flex items-center justify-between">
                            <div>
                                <p class="text-gray-500 text-sm">Tax Liability</p>
                                <p class="text-2xl font-semibold mt-1">$34,876</p>
                            </div>
                            <div class="bg-purple-100 p-3 rounded-full">
                                <i class="fas fa-file-invoice-dollar text-purple-600"></i>
                            </div>
                        </div>
                        <p class="text-gray-500 text-sm mt-2">
                            <i class="fas fa-info-circle mr-1"></i> Due in 14 days
                        </p>
                    </div>
                </div>

                <!-- Payroll Actions -->
                <div class="bg-white rounded-lg shadow mb-6">
                    <div class="p-4 border-b flex justify-between items-center">
                        <h2 class="text-lg font-semibold">Payroll Runs</h2>
                        <div class="flex space-x-2">
                            <button class="px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 flex items-center">
                                <i class="fas fa-plus mr-2"></i> New Payroll Run
                            </button>
                            <button class="px-4 py-2 border border-gray-300 rounded hover:bg-gray-50 flex items-center">
                                <i class="fas fa-file-import mr-2"></i> Import Timesheets
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex space-x-2">
                                <div class="relative">
                                    <select class="appearance-none bg-white border border-gray-300 rounded px-3 py-2 pr-8 focus:outline-none focus:ring-2 focus:ring-blue-500">
                                        <option>All Status</option>
                                        <option>Draft</option>
                                        <option>Pending Approval</option>
                                        <option>Approved</option>
                                        <option>Paid</option>
                                    </select>
                                    <div class="absolute inset-y-0 right-0 flex items-center pr-2 pointer-events-none">
                                        <i class="fas fa-chevron-down text-gray-400"></i>
                                    </div>
                                </div>
                                <div class="relative">
                                    <select class="appearance-none bg-white border border-gray-300 rounded px-3 py-2 pr-8 focus:outline-none focus:ring-2 focus:ring-blue-500">
                                        <option>All Periods</option>
                                        <option>January 2023</option>
                                        <option>February 2023</option>
                                        <option>March 2023</option>
                                    </select>
                                    <div class="absolute inset-y-0 right-0 flex items-center pr-2 pointer-events-none">
                                        <i class="fas fa-chevron-down text-gray-400"></i>
                                    </div>
                                </div>
                            </div>
                            <div class="relative">
                                <input type="text" placeholder="Search..." class="border border-gray-300 rounded px-3 py-2 pl-10 focus:outline-none focus:ring-2 focus:ring-blue-500">
                                <i class="fas fa-search absolute left-3 top-3 text-gray-400"></i>
                            </div>
                        </div>

                        <!-- Payroll Runs Table -->
                        <div class="overflow-x-auto">
                            <table class="min-w-full divide-y divide-gray-200">
                                <thead class="bg-gray-50">
                                    <tr>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Payroll ID</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Period</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Employees</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Gross Pay</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Net Pay</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Status</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Actions</th>
                                    </tr>
                                </thead>
                                <tbody class="bg-white divide-y divide-gray-200">
                                    <tr>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">PR-2023-06-001</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">June 1-15, 2023</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">87</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$124,560.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$89,684.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Approved</span>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                                            <button class="text-blue-600 hover:text-blue-900 mr-3"><i class="fas fa-eye"></i></button>
                                            <button class="text-green-600 hover:text-green-900 mr-3"><i class="fas fa-file-pdf"></i></button>
                                            <button class="text-purple-600 hover:text-purple-900"><i class="fas fa-file-export"></i></button>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">PR-2023-05-002</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">May 16-31, 2023</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">85</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$119,450.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$85,876.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-yellow-100 text-yellow-800">Pending Approval</span>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                                            <button class="text-blue-600 hover:text-blue-900 mr-3"><i class="fas fa-eye"></i></button>
                                            <button class="text-green-600 hover:text-green-900 mr-3"><i class="fas fa-file-pdf"></i></button>
                                            <button class="text-purple-600 hover:text-purple-900"><i class="fas fa-file-export"></i></button>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">PR-2023-05-001</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">May 1-15, 2023</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">84</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$117,320.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$84,456.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-blue-100 text-blue-800">Paid</span>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                                            <button class="text-blue-600 hover:text-blue-900 mr-3"><i class="fas fa-eye"></i></button>
                                            <button class="text-green-600 hover:text-green-900 mr-3"><i class="fas fa-file-pdf"></i></button>
                                            <button class="text-purple-600 hover:text-purple-900"><i class="fas fa-file-export"></i></button>
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>

                <!-- Payroll Details -->
                <div class="bg-white rounded-lg shadow mb-6">
                    <div class="p-4 border-b">
                        <h2 class="text-lg font-semibold">Payroll Details: PR-2023-06-001</h2>
                    </div>
                    <div class="p-4">
                        <div class="flex justify-between items-center mb-4">
                            <div>
                                <p class="text-gray-600">Period: <span class="font-medium">June 1-15, 2023</span></p>
                                <p class="text-gray-600">Status: <span class="font-medium text-green-600">Approved</span></p>
                            </div>
                            <div class="flex space-x-2">
                                <button class="px-4 py-2 bg-green-600 text-white rounded hover:bg-green-700 flex items-center">
                                    <i class="fas fa-file-pdf mr-2"></i> Export Payslips
                                </button>
                                <button class="px-4 py-2 bg-purple-600 text-white rounded hover:bg-purple-700 flex items-center">
                                    <i class="fas fa-file-export mr-2"></i> Bank Export
                                </button>
                                <button class="px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 flex items-center">
                                    <i class="fas fa-envelope mr-2"></i> Email Payslips
                                </button>
                            </div>
                        </div>

                        <!-- Payroll Summary -->
                        <div class="grid grid-cols-1 md:grid-cols-4 gap-4 mb-6">
                            <div class="border rounded-lg p-4">
                                <p class="text-gray-500 text-sm">Gross Pay</p>
                                <p class="text-2xl font-semibold">$124,560.00</p>
                            </div>
                            <div class="border rounded-lg p-4">
                                <p class="text-gray-500 text-sm">Total Deductions</p>
                                <p class="text-2xl font-semibold">$34,876.00</p>
                            </div>
                            <div class="border rounded-lg p-4">
                                <p class="text-gray-500 text-sm">Net Pay</p>
                                <p class="text-2xl font-semibold">$89,684.00</p>
                            </div>
                            <div class="border rounded-lg p-4">
                                <p class="text-gray-500 text-sm">Tax Liability</p>
                                <p class="text-2xl font-semibold">$28,450.00</p>
                            </div>
                        </div>

                        <!-- Employee Payslips Table -->
                        <div class="overflow-x-auto">
                            <table class="min-w-full divide-y divide-gray-200 payslip-table">
                                <thead class="bg-gray-50">
                                    <tr>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Employee</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">ID</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Department</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Gross Pay</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Deductions</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Net Pay</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Status</th>
                                        <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider"></th>
                                    </tr>
                                </thead>
                                <tbody class="bg-white divide-y divide-gray-200">
                                    <!-- Employee 1 -->
                                    <tr class="expandable-row cursor-pointer hover:bg-gray-50" onclick="toggleRow(this)">
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <div class="flex items-center">
                                                <div class="flex-shrink-0 h-10 w-10">
                                                    <img class="h-10 w-10 rounded-full" src="https://ui-avatars.com/api/?name=John+Smith&background=random" alt="">
                                                </div>
                                                <div class="ml-4">
                                                    <div class="text-sm font-medium text-gray-900">John Smith</div>
                                                    <div class="text-sm text-gray-500">john.smith@example.com</div>
                                                </div>
                                            </div>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">EMP-001</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">Engineering</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$5,200.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$1,450.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$3,750.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Processed</span>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                            <i class="fas fa-chevron-down text-gray-400 transition-transform duration-300"></i>
                                        </td>
                                    </tr>
                                    <tr class="expandable-content">
                                        <td colspan="8" class="px-6 py-4 bg-gray-50">
                                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                                <div>
                                                    <h4 class="text-sm font-medium text-gray-900 mb-2">Earnings</h4>
                                                    <table class="min-w-full divide-y divide-gray-200">
                                                        <tbody class="bg-white divide-y divide-gray-200">
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Base Salary</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$4,500.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Overtime (5 hrs)</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$450.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Bonus</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$250.00</td>
                                                            </tr>
                                                            <tr class="font-medium">
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900">Total Earnings</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900 text-right">$5,200.00</td>
                                                            </tr>
                                                        </tbody>
                                                    </table>
                                                </div>
                                                <div>
                                                    <h4 class="text-sm font-medium text-gray-900 mb-2">Deductions</h4>
                                                    <table class="min-w-full divide-y divide-gray-200">
                                                        <tbody class="bg-white divide-y divide-gray-200">
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Federal Tax</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$850.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">State Tax</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$350.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Social Security</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$150.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">401(k) Contribution</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$100.00</td>
                                                            </tr>
                                                            <tr class="font-medium">
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900">Total Deductions</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900 text-right">$1,450.00</td>
                                                            </tr>
                                                        </tbody>
                                                    </table>
                                                </div>
                                            </div>
                                            <div class="mt-4 flex justify-end">
                                                <button class="px-4 py-2 border border-gray-300 rounded text-sm font-medium text-gray-700 hover:bg-gray-50">
                                                    <i class="fas fa-file-pdf mr-2"></i> Download Payslip
                                                </button>
                                            </div>
                                        </td>
                                    </tr>

                                    <!-- Employee 2 -->
                                    <tr class="expandable-row cursor-pointer hover:bg-gray-50" onclick="toggleRow(this)">
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <div class="flex items-center">
                                                <div class="flex-shrink-0 h-10 w-10">
                                                    <img class="h-10 w-10 rounded-full" src="https://ui-avatars.com/api/?name=Sarah+Johnson&background=random" alt="">
                                                </div>
                                                <div class="ml-4">
                                                    <div class="text-sm font-medium text-gray-900">Sarah Johnson</div>
                                                    <div class="text-sm text-gray-500">sarah.johnson@example.com</div>
                                                </div>
                                            </div>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">EMP-002</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">Marketing</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$4,800.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$1,320.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">$3,480.00</td>
                                        <td class="px-6 py-4 whitespace-nowrap">
                                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Processed</span>
                                        </td>
                                        <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                            <i class="fas fa-chevron-down text-gray-400 transition-transform duration-300"></i>
                                        </td>
                                    </tr>
                                    <tr class="expandable-content">
                                        <td colspan="8" class="px-6 py-4 bg-gray-50">
                                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                                <div>
                                                    <h4 class="text-sm font-medium text-gray-900 mb-2">Earnings</h4>
                                                    <table class="min-w-full divide-y divide-gray-200">
                                                        <tbody class="bg-white divide-y divide-gray-200">
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Base Salary</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$4,500.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Commission</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$300.00</td>
                                                            </tr>
                                                            <tr class="font-medium">
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900">Total Earnings</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900 text-right">$4,800.00</td>
                                                            </tr>
                                                        </tbody>
                                                    </table>
                                                </div>
                                                <div>
                                                    <h4 class="text-sm font-medium text-gray-900 mb-2">Deductions</h4>
                                                    <table class="min-w-full divide-y divide-gray-200">
                                                        <tbody class="bg-white divide-y divide-gray-200">
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Federal Tax</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$800.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">State Tax</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$320.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Social Security</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$150.00</td>
                                                            </tr>
                                                            <tr>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500">Health Insurance</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-500 text-right">$50.00</td>
                                                            </tr>
                                                            <tr class="font-medium">
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900">Total Deductions</td>
                                                                <td class="px-4 py-2 whitespace-nowrap text-sm text-gray-900 text-right">$1,320.00</td>
                                                            </tr>
                                                        </tbody>
                                                    </table>
                                                </div>
                                            </div>
                                            <div class="mt-4 flex justify-end">
                                                <button class="px-4 py-2 border border-gray-300 rounded text-sm font-medium text-gray-700 hover:bg-gray-50">
                                                    <i class="fas fa-file-pdf mr-2"></i> Download Payslip
                                                </button>
                                            </div>
                                        </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </div>

    <script>
        // Toggle sidebar
        document.getElementById('toggle-sidebar').addEventListener('click', function() {
            document.querySelector('.sidebar').classList.toggle('collapsed');
        });

        // Toggle expandable rows
        function toggleRow(row) {
            const expandedRow = row.closest('tr');
            const contentRow = expandedRow.nextElementSibling;
            
            expandedRow.classList.toggle('expanded');
            
            const icon = expandedRow.querySelector('i.fa-chevron-down');
            if (expandedRow.classList.contains('expanded')) {
                icon.classList.add('transform', 'rotate-180');
            } else {
                icon.classList.remove('transform', 'rotate-180');
            }
        }

        // Sample data for charts (would be replaced with real data in a production app)
        const payrollData = {
            labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun'],
            grossPay: [100000, 105000, 110000, 115000, 120000, 124560],
            netPay: [72000, 75600, 79200, 82800, 86400, 89684]
        };
    </script>
</body>
</html>
