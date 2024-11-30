temGroup>
  <ItemGroup>
    <ClInclude Include="Source\Hack\Common.h" />
    <ClInclude Include="Source\Overlay\stb_image.h" />
    <ClInclude Include="Source\SDK\AActor.h" />
    <ClInclude Include="Source\SDK\Names.h" />
    <ClInclude Include="Source\SDK\Core.h" />
    <ClInclude Include="Source\Memory\IDA.h" />
    <ClInclude Include="Source\Overlay\Imgui\imconfig.h" />
    <ClInclude Include="Source\Overlay\Imgui\imgui.h" />
    <ClInclude Include="Source\Overlay\Imgui\imgui_impl_dx11.h" />
    <ClInclude Include="Source\Overlay\Imgui\imgui_impl_win32.h" />
    <ClInclude Include="Source\Overlay\Imgui\imgui_internal.h" />
    <ClInclude Include="Source\Overlay\Imgui\imstb_rectpack.h" />
    <ClInclude Include="Source\Overlay\Imgui\imstb_textedit.h" />
    <ClInclude Include="Source\Overlay\Imgui\imstb_truetype.h" />
    <ClInclude Include="Source\Overlay\Overlay.h" />
    <ClInclude Include="Source\Overlay\Renderer.h" />
    <ClInclude Include="Source\Updates.h" />
    <ClInclude Include="Source\Memory\VMProtectSDK.h" />
    <ClInclude Include="Source\Memory\Memory.h" />
    <ClInclude Include="Source\Global.h" />
    <ClInclude Include="Source\SDK\GWorld.h" />
  </ItemGroup>
  <ItemGroup>
    <Library Include="Source\Memory\VMProtectSDK64.lib" />
  </ItemGroup>
  <ItemGroup>
    <Image Include="Source\Images\Vehicles\0.png">
      <ExcludedFromBuild Condition="'$(Configuration)|$(Platform)'=='Debug|x64'">false</ExcludedFromBuild>
      <DeploymentContent Condition="'$(Configuration)|$(Platform)'=='Debug|x64'">false</DeploymentContent>
      <ExcludedFromBuild Condition="'$(Configuration)|$(Platform)'=='Release|x64'">false</ExcludedFromBuild>
      <DeploymentContent Condition="'$(Configuration)|$(Platform)'=='Release|x64'">false</DeploymentContent>
    </Image>
    <Image Include="Source\Images\Vehicles\1.png" />
    <Image Include="Source\Images\Vehicles\10.png" />
    <Image Include="Source\Images\Vehicles\11.png" />
    <Image Include="Source\Images\Vehicles\12.png" />
    <Image Include="Source\Images\Vehicles\13.png" />
    <Image Include="Source\Images\Vehicles\14.png" />
    <Image Include="Source\Images\Vehicles\15.png" />
    <Image Include="Source\Images\Vehicles\16.png" />
    <Image Include="Source\Images\Vehicles\17.png" />
    <Image Include="Source\Images\Vehicles\18.png" />
    <Image Include="Source\Images\Vehicles\2.png" />
    <Image Include="Source\Images\Vehicles\3.png" />
    <Image Include="Source\Images\Vehicles\4.png" />
    <Image Include="Source\Images\Vehicles\5.png" />
    <Image Include="Source\Images\Vehicles\6.png" />
    <Image Include="Source\Images\Vehicles\7.png" />
    <Image Include="Source\Images\Vehicles\8.png" />
    <Image Include="Source\Images\Vehicles\9.png" />
  </ItemGroup>
  <Import Project="$(VCTargetsPath)\Microsoft.Cpp.targets" />
  <ImportGroup Label="ExtensionTargets">
  </ImportGroup>
</Project>
