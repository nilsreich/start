<template>
    <div class="bg-white h-screen flex relative">
        <div class="border-r border-[#e0e0e0]">
            <div class="text-[#0f62fe] p-4">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 32 32">
                    <path d="M16 17v8H6v-8h10m0-2H6a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-8a2 2 0 0 0-2-2ZM27 6v5H17V6h10m0-2H17a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2ZM27 17v5h-5v-5h5m0-2h-5a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2ZM11 6v5H6V6h5m0-2H6a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2Z" />
                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Rectangle&gt;" /> </svg>
            </div>
            <div class="text-black border-l-2 p-3 border-[#0f62fe] bg-[#f4f4f4]">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 32 32">
                    <path d="M26 14h-2v2h2a3 3 0 0 1 3 3v4h2v-4a5 5 0 0 0-5-5ZM24 4a3 3 0 1 1-3 3 3 3 0 0 1 3-3m0-2a5 5 0 1 0 5 5 5 5 0 0 0-5-5Zm-1 28h-2v-2a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v2H9v-2a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5Zm-7-17a3 3 0 1 1-3 3 3 3 0 0 1 3-3m0-2a5 5 0 1 0 5 5 5 5 0 0 0-5-5Zm-8 3H6a5 5 0 0 0-5 5v4h2v-4a3 3 0 0 1 3-3h2ZM8 4a3 3 0 1 1-3 3 3 3 0 0 1 3-3m0-2a5 5 0 1 0 5 5 5 5 0 0 0-5-5Z" />
                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
            </div>
            <div class="text-black p-3 pl-4">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 32 32">
                    <path d="M24 30H8a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v17l-5-3-5 3V4H8v24h16v-4h2v4a2 2 0 0 1-2 2Zm-3-14 3 1V4h-6v13Z" />
                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
            </div>
            <div class="text-black p-3 pl-4 absolute bottom-9">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 32 32">
                    <path d="M26 17v-3h-2v3a1 1 0 0 0 0 1l3 2v2H5v-2l3-2a1 1 0 0 0 0-1v-4a8 8 0 0 1 12-7V4a10 10 0 0 0-3-1V1h-2v2a10 10 0 0 0-9 10v4l-3 2a1 1 0 0 0 0 1v3a1 1 0 0 0 1 1h7v1a5 5 0 0 0 10 0v-1h7a1 1 0 0 0 1-1v-3a1 1 0 0 0 0-1Zm-7 8a3 3 0 0 1-6 0v-1h6Z" />
                    <circle fill="#0f62fe" cx="26" cy="8" r="4" />
                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
            </div>
            <div class="text-black p-3 pl-4 absolute bottom-0">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 32 32"> \
                    <path d="M16 8a5 5 0 1 0 5 5 5 5 0 0 0-5-5Zm0 8a3 3 0 1 1 3-3 3 3 0 0 1-3 3Z" />
                    <path d="M16 2a14 14 0 1 0 14 14A14 14 0 0 0 16 2Zm-6 24v-1a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v1a12 12 0 0 1-12 0Zm14-1a5 5 0 0 0-5-5h-6a5 5 0 0 0-5 5 12 12 0 1 1 16 0Z" />
                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
            </div>
        </div>
        <div class="mx-auto w-full text-black">
                <div class="text-xs font-plex tracking-wide">
                    <div class="flex h-screen px-4 py-4">
                        <div class="flex-1 bg-[#f4f4f4] mr-4">
                            <div class="bg-[#e0e0e0] text-black w-min flex cursor-pointer">
                                <div class="p-4 flex border-r border-[#c6c6c6]">
                                    <div class="whitespace-nowrap">Überschrift 1</div>
                                    <div class="pl-4">
                                        <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 fill-current" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /> </svg>
                                    </div>
                                </div>
                                <div class="p-4">
                                    <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
                                        <path d="M18 25H9V7h9a5 5 0 014 9 5 5 0 01-4 9zm-6-3h6a2 2 0 100-4h-6zm0-7h6a2 2 0 100-5h-6z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4">
                                    <svg class="w-4 h-4 fill-current" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
                                        <path d="M25 9V7H12v2h5l-4 14H7v2h13v-2h-5l4-14h6z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4">
                                    <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                        <path d="M4 26h24v2H4zM16 23a7 7 0 01-7-7V5h2v11a5 5 0 0010 0V5h2v11a7 7 0 01-7 7z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4 border-r border-[#c6c6c6]">
                                    <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                        <path d="M29 23l-6-6v-4a1 1 0 000-1L13 2a1 1 0 00-2 0l-9 9a1 1 0 000 2l10 10a1 1 0 001 0h4l6 6a4 4 0 006-6zM6 10l2 3 2-2-3-2 2-2 4 5 2-2-5-4 2-2 7 7-8 8-7-7zm21 17a2 2 0 01-2 0l-7-6h-5l-1-1 8-8 1 1v5l6 7a2 2 0 010 2z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4 ">
                                    <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                        <path d="M26 18h-2l-2 4-2-4h-2l3 5-3 5h2l2-4 2 4h2l-3-5 3-5z" />
                                        <path fill="#000" d="M19 6V4h-5a2 2 0 00-2 2l-1 7H7v2h4l-1 11H5v2h5a2 2 0 002-2l1-11h5v-2h-5l1-7z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="Transparent Rectangle" /> </svg>
                                </div>
                                <div class="p-4">
                                    <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                        <path d="M10 23l8 3a4 4 0 003-1c2-2 0-6-2-10l6-6 3 2 1-2-3-2 4-4-1-1-5 4c-3-2-7-3-9-1s0 6 1 9l-6 6-3-2-1 2 3 2-5 5V2H2v26a2 2 0 002 2h26v-2H5zm7-16c1-2 3-1 6 1l-5 5c-1-3-2-5-1-6zm0 9c2 3 4 6 2 7-1 2-4 0-7-1z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4">
                                    <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                        <path d="M19 28a3 3 0 01-2-6l5-5a1 1 0 10-2-2l-7 7a4 4 0 01-5 0 3 3 0 010-5l9-9a1 1 0 10-2-2l-9 9-1-2 8-8a3 3 0 015 5l-8 8a1 1 0 000 2 1 1 0 002 0l6-6a3 3 0 115 4l-5 6a1 1 0 002 2l5-5 1 2-4 4a3 3 0 01-3 1z" />
                                        <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                </div>
                                <div class="p-4 text-black flex">
                                    <div>
                                        <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                            <path d="M31 24h-4v-4h-2v4h-4v2h4v4h2v-4h4v-2z" />
                                            <path d="M25 5h-3V4a2 2 0 00-2-2h-8a2 2 0 00-2 2v1H7a2 2 0 00-2 2v21a2 2 0 002 2h10v-2H7V7h3v3h12V7h3v9h2V7a2 2 0 00-2-2zm-5 3h-8V4h8z" />
                                            <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                    </div>
                                </div>
                                                        <div class=" p-4 ">
                                <svg class="fill-current w-4 h-4" viewBox="0 0 32 32">
                                    <path d="M21 26H4a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h17a2 2 0 0 1 2 2v4l5.4-3.8A1 1 0 0 1 30 9v14a1 1 0 0 1-1.6.8L23 20v4a2 2 0 0 1-2 2ZM4 8v16h17v-6a1 1 0 0 1 1.6-.8L28 21V10.9l-5.4 4A1 1 0 0 1 21 14V8Z" />
                                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                            </div>
                            <div class=" p-4 ">
                                <svg class="fill-current w-4 h-4" viewBox="0 0 32 32">
                                    <path d="M9.2 18.6A7.4 7.4 0 0 1 9 17v-3H7v3a8.8 8.8 0 0 0 .6 3.2ZM13 15V7a3 3 0 0 1 6 0v1.8l2-2A5 5 0 0 0 11 7v8Zm10 2a7 7 0 0 1-11.7 5.1l1.4-1.4A5 5 0 0 0 21 17v-4.6l9-9L28.6 2 2 28.6 3.4 30l6.5-6.4a9 9 0 0 0 5.1 2.3V28h-4v2h10v-2h-4v-2a9 9 0 0 0 8-9v-3h-2Zm-4 0a3 3 0 0 1-4.9 2.3l4.9-4.9Z" />
                                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                            </div>
                            <div class="bg-[#da1e28] p-4">
                                <svg class="fill-current w-4 h-4" viewBox="0 0 32 32">
                                    <path d="M16 4A12 12 0 1 1 4 16 12 12 0 0 1 16 4m0-2a14 14 0 1 0 14 14A14 14 0 0 0 16 2Z" />
                                    <path d="M20 12v8h-8v-8h8m0-2h-8a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2v-8a2 2 0 0 0-2-2Z" />
                                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                            </div>
                            </div>
                            <div class="text-black cursor-text p-4">
                                <div class="text-lg">Lineare Funktionen</div>
                            </div>
                        </div>
                        <div class=" w-60 relative bg-[#f4f4f4]">
                                <div class="">
                                    <div class="flex text-sm">
                                        <div class="border-t-2 p-3 pr-6 font-semibold border-[#0f62fe]">Assistant</div>
                                        <div class="border-b-2 p-3 pr-6 border-[#e0e0e0] bg-[#e0e0e0]">Communication</div>
                                    </div>
                                    <div class="p-4">
                                        <div class="text-right">Definiere lineare Funktionen</div>
                                        <div class="border-[#0f62fe] border-l">
                                            <div class="p-3"> Eine Funktion ist eine Eindeutige Zuordnung die jedem x-Wert aus der Definitionsmenge einen y-Wert aus der Wertemenge zuordnet
                                                <div class="text-[#0f62fe] w-7 mt-3 border border-[#0f62fe] cursor-pointer hover:bg-[#0f62fe] hover:text-black">
                                                    <div class="p-1">
                                                        <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                                            <path d="M17 15V8h-2v7H8v2h7v7h2v-7h7v-2z" />
                                                            <path fill="none" d="M0 0h32v32H0z" /> </svg>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="my-5">
                                            <div class="text-right">3+6-2</div>
                                        </div>
                                        <div class="border-l border-[#0f62fe]">
                                            <div class="p-3"> 3+6-2=4
                                                <div class="text-[#0f62fe] w-7 mt-3 border border-[#0f62fe] cursor-pointer hover:bg-[#0f62fe] hover:text-black">
                                                    <div class="p-1">
                                                        <svg class="w-4 h-4 fill-current" viewBox="0 0 32 32">
                                                            <path d="M17 15V8h-2v7H8v2h7v7h2v-7h7v-2z" />
                                                            <path fill="none" d="M0 0h32v32H0z" /> </svg>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="absolute bottom-0 flex w-full border-t h-12 border-[#6f6f6f] p-4 left-0">
                                            <div class="cursor-text text-[#6f6f6f]">Schreibe eine Nachricht</div>
                                            <div class="px-2 flex-1">
                                                <svg class="w-4 h-4 cursor-pointer fill-current" viewBox="0 0 32 32">
                                                    <path d="m27.4 15.1-22-11a1 1 0 0 0-1 .1 1 1 0 0 0-.4 1L7 16 4 26.7A1 1 0 0 0 5 28a1 1 0 0 0 .5-.1l22-11a1 1 0 0 0 0-1.8Zm-20.8 10L8.8 17H18v-2H8.8L6.5 6.9 24.9 16Z" />
                                                    <path fill="none" d="M0 0h32v32H0z" data-name="&lt;Transparent Rectangle&gt;" /> </svg>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                        </div>
                    </div>
    
            </div>
        </div>
    </div>
  </div>
</template>
