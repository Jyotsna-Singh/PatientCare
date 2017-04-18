<p align="center">
  <br><br>
  <img src="https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/logo.PNG">
</p>

[![License](https://img.shields.io/packagist/l/cakephp/app.svg?style=flat-square)](http://jyotsnasingh.com/projects/CakePHP/PatientCare/)

**PatientCare** is a Patient Manager admin tool for clinics and hospitals. It is built using the CakePHP 3 framework. Admin can create,view,edit,delete the following: Patients, Doctors, Appointments, Carriers, Invoices. Admin can also view and manage other users.

* Features/Technologies: 
  * CakePHP 3.3.13
  * MVC, PHP OOP, PHPMyAdmin
  * MySQL CRUD, Superglobals (GET, POST)

## Version
1.0.0

## Live Demo - PatientCare
 [![alt tag](https://github.com/Jyotsna-Singh/SearchVidz-YoutubeAPI/blob/master/img/red-button.PNG)](http://jyotsnasingh.com/projects/CakePHP/PatientCare/)


## Usage

**List Patients** | **View Patient Details**
--- | ---
List Patients | View Patient Details
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/patients.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/view-patient.PNG)

**Edit Patient Details** | **Add New Patient**
--- | --- 
Edit Patient Details | Add New Patient  
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/edit-patient.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/add-patient.PNG) 

**List Doctors** | **View Doctor Details**
--- | ---
List Doctors | View Doctor Details
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/doctors.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/view-doctor.PNG)

**Edit Doctor Details** | **Add New Doctor**
--- | --- 
Edit Doctor Details | Add New Doctor  
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/edit-doctor.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/add-doctor.PNG) 

**List Carriers** | **View Carrier Details**
--- | ---
List Carriers | View Carrier Details
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/carriers.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/view-carrier.PNG)

**Edit Carrier Details** | **Add New Carrier**
--- | --- 
Edit Carrier Details | Add New Carrier  
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/edit-carrier.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/add-carrier.PNG) 

**List Appointments** | **View Appointment Details**
--- | ---
List Appointments | View Appointment Details
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/appointments.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/view-appointment.PNG)

**Edit Appointment Details** | **Add New Appointment**
--- | --- 
Edit Appointment Details | Add New Appointment  
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/edit-appointment.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/add-appointment.PNG) 

**List Invoices** | **View Invoice Details**
--- | ---
List Invoices | View Invoice Details
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/invoices.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/view-invoice.PNG)

**Edit Invoice Details** | **Add New Invoice**
--- | --- 
Edit Invoice Details | Add New Invoice  
![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/edit-invoice.PNG)  | ![alt text](https://github.com/Jyotsna-Singh/PatientCare/blob/master/webroot/img/add-invoice.PNG) 


## Vendors
CakePHP - [http://cakephp.org/](http://cakephp.org/)  
 


## License
MIT License


# CakePHP Application Skeleton

[![Build Status](https://img.shields.io/travis/cakephp/app/master.svg?style=flat-square)](https://travis-ci.org/cakephp/app)
[![License](https://img.shields.io/packagist/l/cakephp/app.svg?style=flat-square)](https://packagist.org/packages/cakephp/app)

A skeleton for creating applications with [CakePHP](http://cakephp.org) 3.x.

The framework source code can be found here: [cakephp/cakephp](https://github.com/cakephp/cakephp).

## Installation

1. Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist cakephp/app [app_name]`.

If Composer is installed globally, run

```bash
composer create-project --prefer-dist cakephp/app
```

In case you want to use a custom app dir name (e.g. `/myapp/`):

```bash
composer create-project --prefer-dist cakephp/app myapp
```

You should now be able to visit the path to where you installed the app and see the default home page.

### Installation of 3.next

In case you want to try the unstable branch:

```bash
composer create-project --prefer-dist cakephp/app=dev-3.next app
```

You may then install specific RC, for example:

```bash
cd app;
composer require cakephp/cakephp:3.4.0-RC3
```

## Update

Since this skeleton is a starting point for your application and various files would have been modified as per your needs, there isn't a way to provide automated upgrades, so you have to do any updates manually.

## Configuration

Read and edit `config/app.php` and setup the `'Datasources'` and any other
configuration relevant for your application.

## Layout
The app skeleton uses a subset of [Foundation](http://foundation.zurb.com/) CSS framework by default. You can, however, replace it with any other library or custom styles.
