.. image:: https://travis-ci.org/Legrandin/pycryptodome.svg?branch=master
   :target: https://travis-ci.org/Legrandin/pycryptodome

.. image:: https://ci.appveyor.com/api/projects/status/mbxyqdodw9ylfib9/branch/master?svg=true
   :target: https://ci.appveyor.com/project/Legrandin/pycryptodome

PyCryptodome
============

PyCryptodome is a self-contained Python package of low-level
cryptographic primitives.

It supports Python 2.4 or newer, all Python 3 versions and PyPy.

You can install it with a simple::

	pip install pycryptodome

PyCryptodome is a fork of PyCrypto. It brings the following enhancements
with respect to the last official version of PyCrypto (2.6.1):

* Authenticated encryption modes (GCM, CCM, EAX, SIV, OCB)
* Accelerated AES on Intel platforms via AES-NI
* First class support for PyPy
* SHA-3 (including SHAKE XOFs) and BLAKE2 hash algorithms
* Salsa20 and ChaCha20 stream ciphers
* scrypt and HKDF
* Deterministic DSA
* Password-protected PKCS#8 key containers
* Shamir's Secret Sharing scheme
* Random numbers get sourced directly from the OS (and not from a CSPRNG in userspace)
* Simplified install process, including better support for Windows
* Cleaner RSA and DSA key generation (largely based on FIPS 186-4)
* Major clean ups and simplification of the code base

For more information, see the `homepage`_.

.. _`homepage`: http://www.pycryptodome.org

