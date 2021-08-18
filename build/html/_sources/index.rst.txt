======================================
CaesarsCipher Documentation
======================================

Introduction
============

This is a simple python package for encrypting and decrypting text in Caesar's Cipher.

.. note::
    This documentation was generated on Aug 18, 2021. Version 0.0.3


Installation
============

Install the CaesarsCipher package using PIP ::

   pip install CaesarsCipher


Usage
===========
How To Use The CaesarsCipher package

.. code-block:: python
   :linenos:

   # Import The Ceaser Class From The CeasersCipher Module
   from CaesarsCipher import Caesar

   # Encrypt Your Text Using Ceaser.encrypt('your_text_here',shift_value)
   print(Caesar.encrypt("Aaron Fritz",10))
   
   # If You Don't Specify Shift Value In The Function For Encryption, The Default Shift Will Be 10
   print(Caesar.encrypt("Aaron Fritz",10))
   
   # Decrypt Your Text Using Ceaser.decrypt('your_text_here',shift_value)
   print(Caesar.decrypt("Kkbyx Pbsdj",10))
   
   # If You Dont Know The Shift Value, Decrypt Your Text Using Ceaser.decrypt('your_text_here') for Brute Force Decryption
   print(Caesar.decrypt("Kkbyx Pbsdj"))





